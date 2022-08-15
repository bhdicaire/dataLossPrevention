![dataLossPrevention logo](https://github.com/bhdicaire/dataLossPrevention/raw/master/logo.png)

You’ve been there too — setting up a data loss prevention solution might be a damn long project (DLP), if you need to _support multiple languages_ and don’t have [adequate data sources](dataSets/source.md).

This repository consolidate Data Loss/Leak Prevention insight and [sample files (e.g., datasets)](dataSets/README.md), that I have collected and used over the years. Your quality assurance library does not have to be unique, everyone strives for consistency. 

Fork this repository, and improve _your_ library. Even better, send me an update :laughing:.

> **A DLP solution is a set of enterprise processes, [tools, and techniques](techniques/README.md) that monitor sensitive information and prevent data exfiltration.**

## What problem does it solve and why is it useful?

I wasn't happy with the provided bundle of mock files to test my DLP policies and [demonstrate compliance](techniques/compliance.md). They were either [too simple or not localized for my use case](dataSets/README.md).

Friend don’t let friends test the effectiveness of a DLP solution with production data. You need _realistic test data[^1]_ in several formats such as CSV, JSON, SQL, TXT, and Excel to make sure your DLP Policies are working correctly especially after a significant change. 

_dataLossPrevention_ by Benoît H. Dicaire is shared with an [unlicense](LICENSE). For more information, please refer to [unlicense.org](https://unlicense.org).

[^1]: Refer to the [sensitive information type entity definitions provided by Microsoft](https://docs.microsoft.com/en-us/microsoft-365/compliance/sensitive-information-type-entity-definitions?view=o365-worldwide) for more information about the required structure.

### Fake sensitive information generators

 
| Name | Cybersecurity | Finance | Legal | Personal | Technology |
| :-- | :--: | :--:| :--: | :--:| :--: |
|[DLP Test](https://dlptest.com/)| X | X | X | X | X |
|[Fake Person Generator](https://www.fakepersongenerator.com/)| X | X | X | X | X |
|[Fake Generator](https://fakegenerator.net/)| X | X | X | X | X |
|[GenerateData.com](https://generatedata.com/)[^2]| X | X | X | X | X |
|[Get Fake Data](https://getfakedata.com/)| X | X | X | X | X |
|[Get Bored Human](https://boredhumans.com/faces.php)| X | X | X | X | X |
|[Mockaroo](https://www.mockaroo.com/)| X | X | X | X | X |
|[Mock Turtle](https://mockturtle.net/)| X | X | X | X | X |
|[Venkom](https://cloud.venkon.us/)| X | X | X | X | X |

[^2]:Source code is available [on GitHub/benkeen/generatedata](https://github.com/benkeen/generatedata)

You can also search on GitHub for library code and C tool related to [data-generator](https://github.com/topics/data-generator), [fake-data](https://github.com/topics/fake-data), [mock-data ](https://github.com/topics/mock-data), [mock-data-generator](https://github.com/topics/mock-data-generator), and [test data](https://github.com/topics/test-data).
