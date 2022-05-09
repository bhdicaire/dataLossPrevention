![dataLossPrevention logo](https://github.com/bhdicaire/dataLossPrevention/raw/master/logo.png)

This repository consolidate DLP sample files that I have collected and used over the years. Your quality assurance library does not have to be unique, everyone strives for consistency. 

Fork this repository, and improve _your_ library. Even better, send me an update :laughing:.

> **A DLP solution is a set of processes, [tools, and techniques](techniques.md) that monitor sensitive information and prevent data exfiltration.**

## What problem does it solve and why is it useful?

I wasn't happy with the provided bundle of fake files to test my DLP policies. They were either too simple or not localized for my use case.

## Datasets

You’ve been there too — setting up a data loss prevention solution is a damn long project (DLP) especially if you need to support _multiple languages_. I have used several [data generators](techniques.md#tools) to obtain American, Canadian, European specific datasets.

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
