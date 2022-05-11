![dataLossPrevention logo](https://github.com/bhdicaire/dataLossPrevention/raw/master/logo.png)

This repository consolidate Data Loss/Leak Prevention (DLP) sample files (e.g., datasets) that I have collected and used over the years. Your quality assurance library does not have to be unique, everyone strives for consistency. 

Fork this repository, and improve _your_ library. Even better, send me an update :laughing:.

> **A DLP solution is a set of enterprise processes, [tools, and techniques](techniques.md) that monitor sensitive information and prevent data exfiltration.**

## What problem does it solve and why is it useful?

I wasn't happy with the provided bundle of fake files to test my DLP policies. They were either too simple or [not localized for my use case](dataSets/README.md#Localization).

## Datasets

You’ve been there too — setting up a data loss prevention solution is a damn long project (DLP) especially if you need to _support multiple languages_. I have used several [data generators](datasets/README.md#Fake) to obtain American, Canadian, and European specific datasets.

<details>
<summary>Cybersecurity</summary>
<br>
Items:
  * password/ shadow
  * ldap
  
Compliance:
  * To be defined
  
</details>
<details>
<summary>Finance</summary>
<br>
Items:
  * Credit card number (CCN)
  
Compliance:
  * PCI
  
</details>
<details>
<summary>Industry</summary>
<br>
Items:
  * [Pharmaceutical product documents by Brian Reid](https://c7solutions.com/2014/04/dlp-templates)
  * NDA
  
Compliance:
  * To be defined
  
</details>
<details>
<summary>Legal</summary>
<br>
Items:
  * Contract
  * NDA
  
Compliance:
  * To be defined
  
</details>
<details>
<summary>Personal</summary>
<br>
Items:
  * PII
  * PHI
 
 
| File Name   | Description |
| :-- |:-- | 
|[lastName.US.txt](personal/lastName.US.txt)| Last names occurring 100 or more times from the [US Census Bureau (up to the year 2000)](https://www.census.gov/topics/population/genealogy/data/2000_surnames.html) Because of a 72-year restriction on access to the _full_ Census, the most recent year available is 1950, released on April 1, 2022. |

| Country   | Code |
| :-- |:-- | 
| Netherlands | NL |
| Norway | NO |
| Swiss | CH |
| United States of America | US |
| Swedish | SE |
| Netherlands | NL |

Compliance:
  * GDPR


 
 
  
</details>
<details>
<summary>Technology</summary>
<br>
Items:
  * ldap
  * code
  
  
Compliance:
  * To be defined
  
</details>

## _dataLossPrevention_ by Benoît H. Dicaire is shared with an [unlicense](LICENSE).
For more information, please refer to <https://unlicense.org>
