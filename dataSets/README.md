# Datasets

 I have used [curated data resources](source.md) and several [data generators](#KnownDataGenerators) and to obtain _good enough_ American, Canadian, and European specific datasets.

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
 
 
| File Name   | Description |
| :-- |:-- | 
|[lastName.US.txt](personal/lastName.US.txt)| Last names occurring 100 or more times from the [US Census Bureau (up to the year 2000)](https://www.census.gov/topics/population/genealogy/data/2000_surnames.html) Because of a 72-year restriction on access to the _full_ Census, the most recent year available is 1950, released on April 1, 2022. |

https://github.com/orgs/unitedstates

Compliance:
  * GDPR

</details>
