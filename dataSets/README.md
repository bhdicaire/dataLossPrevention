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
  * LDAP[^1]: LDF[^2]schema to store content & actions to perform such as a adding, modifying, removing and renaming objects (e.g., users and groups)
* [base-64](https://en.wikipedia.org/wiki/Base64) encoded files
* ICS/SCADA[^3]

Compliance:
  * To be defined

[^1]: Lightweight Directory Access Protocol (LDAP), [OpenLDAP](https://www.openldap.org/) is an open source implementation 
[^2]: The LDAP Data Interchange Format (LDIF) is stored as plain-text files with an LDF extension
[^3]: Industrial Control System (Ics) / Supervisory Control and Data Acquisition (SCADA)
  
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
<summary>Industries</summary>
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
<summary>International</summary>
<br>

Items:
  * Contract
  * NDA

# Countries

## United Nation country names
The [United Nations (UN) group of experts on geographical names ](https://unstats.un.org/unsd/geoinfo/UNGEGN/docs/26th-gegn-docs/WP/WP54_UNGEGN%20WG%20Country%20Names%20Document%202011.pdf) document the short and the formal countries names for the official national languages and the UN official languages (e.g. English, French, Spanish, Russian, Chinese, and Arabic).

## ISO 3166 country codes (2013 edition)

[ISO 3166 is the International Standard for country codes](https://www.iso.org/iso-3166-country-codes.html), codes for subdivisions and formerly used codes (codes that were once used to describe countries but are no longer in use).

The country codes can be represented either as a two-letter code (alpha-2) which is recommended as the general purpose code, a three-letter code (alpha-3) which is more closely related to the country name and a three digit numeric code (numeric -3) which can be useful if you need to avoid using Latin script.

Names and codes for subdivisions are usually taken from relevant official national information sources.



  
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
