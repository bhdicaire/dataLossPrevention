# Datasets

 I have used [curated data resources](source.md) and several [data generators](../README.md/#KnownDataGenerators) and to obtain _good enough_ American, Canadian, and European specific datasets.

It’s essential to support country specific localisation (l10n) as an integral part of your policies to reduce false positive and false negative. The flexibility provided by the internationalisation (i18n) to ensure that DLP policies can be adapted to various languages and regions without engineering changes.

The datasets are identified with the country ISO code except for generic english document.

| Country   | Code |
| :-- |:-- | 
| Canada | CA |
| Federal Republic of Germany | DE |
| French Republic | FR |
| Hellenic Republic | GR |
| Kingdom of Belgium | BE |
| Kingdom of Norway| NO |
| Kingdom of Sweden| SE |
| Kingdom of the Netherlands | NL |
| Portugal | PT |
| Republic of Finland | FI |
| Swiss Confederation | CH |
| United States of America | US |

## Datasets

<details>
<summary>Secrets</summary>
<br>

Items:
  * password files / shadow
  * common passwords
  * LDAP[^1]: LDF[^2]schema to store content actions to perform such as a adding, modifying, removing and renaming objects (e.g., users and groups)
* [base-64](https://en.wikipedia.org/wiki/Base64) encoded files

Compliance:
  * To be defined

[^1]: Lightweight Directory Access Protocol (LDAP), [OpenLDAP](https://www.openldap.org/) is an open source implementation 
[^2]: The LDAP Data Interchange Format (LDIF) is stored as plain-text files with an LDF extension
  
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
<summary>Information Technology (IT)</summary>
<br>




Items:

  * [A list of free email provider domains](https://gist.github.com/tbrianjones/5992856) curated by [T. Brian Jones](https://github.com/tbrianjones)
  * ldap
  * code
  
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
 
 

Compliance:
  * GDPR

</details>
