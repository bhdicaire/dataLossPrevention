# DLP Tools and techniques

> FYI: Data Loss Prevention is also known as Data Leakage Prevention (DLP) 
## Techniques


### File size and type

A file size filter checks for files with a specific size to perform configured DLP evaluation.

A file type rule allows you to allow, block, quarantine, and log based on the file type. the file type can be identified by the [file extension](https://file-extension.net/seeker/), the [file magic id](https://en.wikipedia.org/wiki/List_of_file_signatures). You can also use a code library to identify unrecognized or unknown file types supported by a database of recognized file formats.

It’s a good practice to use the code library against all files to ensure that the file is actually of the type indicated. Of course, the file format dataset should be regularly updated.

### Predefined Expressions

identifying sensitive information with minimal risk of transcription errors

Names from the US Census Bureau (up to the year 1990)

IBAN (International Bank Account Number)

Most credit cards and many government identification numbers use the algorithm as a simple method of distinguishing valid numbers from mistyped or otherwise incorrect numbers. ISO/IEC 7812-1:2017 specifies a numbering system for the identification of the card issuers, the format of the issuer identification number (IIN) and the primary account number (PAN).
https://www.iso.org/standard/70484.html

https://en.wikipedia.org/wiki/Luhn_algorithm
German computer scientist Hans Peter Luhn developed the Luhn algorithm in 1954. It calculates simple checksum formula used to validate identification numbers The algorithm was designed to protect against accidental errors, such as digit mistyping. It will detect any single-digit error, as well as almost all transpositions of adjacent digits. However, it will not detect transposition of the two-digit sequence 09 to 90 (or vice versa).

### REGEX

Expressio n-specific checksum

### Fingerprinting
Most DLP solutions can _fingerprint_ unstructured data within a file by algorithms that map the content to checksums. The DLP engine uses the checksums to detect outbound documents containing the same pattern. If a match is found, the configured action is taken. 

Of course, the fingerprinting module will not evaluate password protected files, picture, and image-only PDF documents that contain just the scanned/photographed images of pages, without an underlying text layer.
files that contain only images.

#### Forms and templates
It’s a good practice to fingerprint template and then create a DLP policy that detects and blocks this kind of document with sensitive content filled in. 

I usually start with government, and human resources forms. You should update forms created specifically for your organization with a non printable ID to ease the identification and reduce false positive.

#### Intellectual Property

https://www.gutenberg.org/ebooks/
https://openlibrary.org/explore

## Tools

### Testing Resource 

| Name   | HTTP Post | HTTPS Post | FTP |
| :-- |:--: | :--:| :--: |
|[DLP Test](https://dlptest.com/)| X | X | X |
|[NetMask.US](http://www.netmask.us/dlptest)| X | X | X |
|| X | X | X |
http://www.testtheproxy.com/
