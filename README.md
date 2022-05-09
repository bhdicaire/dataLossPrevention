![dataLossPrevention logo](https://github.com/bhdicaire/dataLossPrevention/raw/master/logo.png)

This repository consolidate DLP sample files that I have collected and used over the years. Your quality assurance library does not have to be unique, everyone strives for consistency. Fork this repository, customize, and improve _your_ library. Even better, send me an update :)

> A DLP solution is a set of processes, [tools, and techniques](techniques.md) that monitor and prevent data exfiltration.

## What problem does it solve and why is it useful?

I wasn't happy with the provided bundle of fake files to test my DLP policies. They were either too simple or not localized for my use case.

## Datasets

You’ve been there too — setting up a data loss prevention solution is a damn long project (DLP) especially if you need to support multiple languages.

I have used several data generators to obtain American, Canadian, European specific datasets. My themes are cybersecurity, finance, legal, personal, and technology.

| Name | Cybersecurity | Finance | Legal | Personal | Technology |
|:----------|--|--:|--:|--:|--:|
|[DLP Test](https://dlptest.com/)| X | X | X | X | X |
|[Fake Person Generator](https://www.fakepersongenerator.com/)| X | X | X | X | X |
|[Fake Generator](https://fakegenerator.net/)| X | X | X | X | X |
|[Get Fake Data](https://getfakedata.com/)| X | X | X | X | X |
|[Get Bored Human)](https://boredhumans.com/faces.php)| X | X | X | X | X |
|[Venkom](https://cloud.venkon.us/)| X | X | X | X | X |

<details>
<summary>Cybersecurity</summary>

Items:
  * password/ shadow
  * ldap
  
  
Compliance:
  * To be defined
  
</details>

<details>
<summary>Finance</summary>

Items:
  * Credit card number (CCN)
  
Compliance:
  * PCI
  
</details>
<details>
<summary>Legal</summary>

Items:
  * Contract
  * NDA
  
Compliance:
  * To be defined
  
</details>
<details>
<summary>Personal</summary>

Items:
  * PII
  * PHI
  
Compliance:
  * GDPR
  
</details>
<details>
<summary>Technology</summary>

Items:
  * ldap
  * code
  
  
Compliance:
  * To be defined
  
</details>
## _dataLossPrevention_ by Benoît H. Dicaire is shared with an [unlicense](https://github.com/bhdicaire/visioStencils/raw/main/LICENSE).
For more information, please refer to <https://unlicense.org>
