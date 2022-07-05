# DLP Tools and techniques

> FYI: Data Loss Prevention is also known as Data Leakage Prevention (DLP) 

## Tools

Testing Resource 

| Name   | HTTP Post | HTTPS Post | FTP |
| :-- |:--: | :--:| :--: |
|[DLP Test](https://dlptest.com/)| X | X | X |
|[NetMask.US](http://www.netmask.us/dlptest)| X | X | X |
|[Test the Proxy](http://www.testtheproxy.com/)| X | X | X |

## Techniques



### File size and type

A file size filter checks for files with a specific size to perform configured DLP evaluation.

A file type rule allows you to allow, block, quarantine, and log based on the file type. the file type can be identified by the [file extension](https://file-extension.net/seeker/), the [file magic id](https://en.wikipedia.org/wiki/List_of_file_signatures). You can also use a code library to identify unrecognized or unknown file types supported by a database of recognized file formats.

It’s a good practice to use the code library against all files to ensure that the file is actually of the type indicated. Of course, the file format dataset should be regularly updated.

### Predefined Expressions

A predefined expression usually stored as a single reference item or in a dictionary to identify sensitive information with minimal risk of transcription errors. Also use match ...

Most credit cards and many government identification numbers use  algorithms as a simple method of distinguishing valid numbers from mistyped or otherwise incorrect numbers:
 * [Luhn_algorithm[^1]](https://en.wikipedia.org/wiki/Luhn_algorithm) developed in 1954 to validate identification numbers based on a simple checksum
 * ISO/IEC 7812-1:2017 specifies a numbering system for the identification of the card issuers, the format of the issuer identification number (IIN) and the primary account number (PAN).
* ISO 7084 https://www.iso.org/standard/70484.html

[^1]:The algorithm was designed to protect against accidental errors, such as digit mistyping. It will detect any single-digit error, as well as almost all transpositions of adjacent digits. 

Names from the US Census Bureau (up to the year 1990)

IBAN (International Bank Account Number)

### Regular Expression (RegEx)

Expression-specific checksum

### Exact Data Match (EDM)
Most DLP solutions can _fingerprint_ structured and unstructured data with an algorithms that map the content to checksums. The DLP engine uses the checksums to detect outbound documents containing the same pattern. If a match is found, the configured action is taken. 

Of course, the fingerprinting module will not evaluate password protected files, picture, and image-only PDF documents that contain just the scanned/photographed images of pages, without an underlying text layer.
files that contain only images.

#### Intellectual Property

  * https://www.gutenberg.org/ebooks/
  * https://openlibrary.org/explore

#### Forms and templates
It’s a good practice to fingerprint template and then create a DLP policy that detects and blocks this kind of document with sensitive content filled in. 

I usually start with government, and human resources forms. You should update forms created specifically for your organization with a non printable ID to ease the identification and reduce false positive.
