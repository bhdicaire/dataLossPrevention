# Tools and techniques

## Techniques


### File size and type

A file size filter checks for files with a specific size to perform configured DLP evaluation.

A file type rule allows you to allow, block, quarantine, and log based on the file type. the file type can be identified by the [file extension](https://file-extension.net/seeker/), the [file magic id](https://en.wikipedia.org/wiki/List_of_file_signatures). You can also use a code library to identify unrecognized or unknown file types supported by a database of recognized file formats.

It’s a good practice to use the code library against all files to ensure that the file is actually of the type indicated. Of course, the file format dataset should be regularly updated.

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
| :----------| :--------: | :--:|--|
|[DLP Test](https://dlptest.com/)| X | X | X |


| Syntax    | Description |   Test Text |
| :-------- | :---------: | ----------: |
| Header    |    Title    | Here's this |
| Paragraph |    Text     |    And more |

### Known Data Generator
 
| Name | Cybersecurity | Finance | Legal | Personal | Technology |
|:----------|--|--:|--:|--:|--:|
|[DLP Test](https://dlptest.com/)| X | X | X | X | X |
|[Fake Person Generator](https://www.fakepersongenerator.com/)| X | X | X | X | X |
|[Fake Generator](https://fakegenerator.net/)| X | X | X | X | X |
|[Get Fake Data](https://getfakedata.com/)| X | X | X | X | X |
|[Get Bored Human)](https://boredhumans.com/faces.php)| X | X | X | X | X |
|[Venkom](https://cloud.venkon.us/)| X | X | X | X | X |
