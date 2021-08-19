# ActiveQuery Contribution Policy

[![](https://gpvc.arturio.dev/ActiveQ)](#)
[![](https://img.shields.io/badge/Coverage-100%25-brightgreen)](#)
[![](https://img.shields.io/badge/Open%20Source%20License-OSL%203.0-brightgreen)](#)
[![](https://img.shields.io/badge/ActiveQuery%20Complance%Framework-v21.0-brightgreen)](#)


[![](https://img.shields.io/badge/Ethical%20Source%20Policy-1F618D)](#)
[![](https://img.shields.io/badge/Contributors%20Covenant-1F618D)](#)
[![](https://img.shields.io/badge/Open%20Source%20Software%20Covenant-1F618D)](#)
[![](https://img.shields.io/badge/Inclusive%20Community-1F618D)](#)
[![](https://img.shields.io/badge/Ethical%20Community%Inclusion-1F618D)](#)
[![](https://img.shields.io/badge/Ethical%20Accessibility-1F618D)](#)
[![](https://img.shields.io/badge/Ethical%20Privacy-1F618D)](#)
[![](https://img.shields.io/badge/Ethical%20Compensation-1F618D)](#)


[![](https://img.shields.io/badge/ActiveQuery%20Cascading%20Style%20Sheets%20(AQCSS)™-76448A)](#)
[![](https://img.shields.io/badge/ActiveQuery%20Cascading%20JavaScript%20(AQJS)™-76448A)](#)
[![](https://img.shields.io/badge/ActiveQuery%20Intelligence%20(AQI)™-76448A)](#)
[![](https://img.shields.io/badge/ActiveQuery%20Progressive%20Enhancement%20(AQPE)™-76448A)](#)
[![](https://img.shields.io/badge/ActiveQuery%20Stream%20(AQS)™-76448A)](#)
[![](https://img.shields.io/badge/ActiveQuery%20Keep%20It%20Simple%20Smart%20(AQKISS)™-76448A)](#)
[![](https://img.shields.io/badge/ActiveQuery%20Open%20Source%20Software%20(AQOSS)-76448A)](#)

ActiveQuery (synonymous with "Active Query" and wheresoever abbreviated as "ActiveQ" 
or "AQ", whether upper cased, lower cased or capitalised) and applies to all parts of 
ActiveQuery projects, programmes, respositeries, and spaces. 

ActiveQuery is group open source projects that are under very active development. 
There's always more to be done and We are always working on making contributing to 
projects as easy, inclusive and transparent as possible. ActiveQuery welcomes anyone 
willing to put in the time and effort to help us and our community of users.

This document will help answer common questions that you may have.

## 1. Code of Conduct

ActiveQuery has incorporated the Contributor Covenant as its [Code of Conduct Policy](CODE_OF_CONDUCT_POLICY.md) and 
we expect all participants to strictly adhere to it. In order to grasp wider understanding 
as to what actions will and will  not be tolerated, it is recommended that read full text 
before proceeding.

## 2. Open Development

In the spirit of Open Source Software Development (OSSD) To maintain seamless collaboration 
without compromising the integrity, all of our work happens and directly goes on to Open Core 
DevOps platforms such as GitHub or GitLab. However this enevtiably brings practical, political, 
economic and ethical ramifications challanges for software development and software use in 
modren era. 

ActiveQuery has incorporated [Ethical Source Princpels](ETHICAL_SOURCE_POLICY.md) and 
expect all participants  to adhere to them. In order to grasp wider understanding as to what is 
involved, it is recommended that you read full text before proceeding.

## 3. Open Source Software License (OSSL)

ActiveQuery is Open Source Software (OSS) by intent, and has adopted Terms & Conditions 
of [Open Software License v. 3.0 (OSL-3.0)](LICENSE.md), except where indicated. 
Needless to say all dependencies included and distributed with ActiveQuery must be 
compatible with this license.

ActiveQuery Compliance Team will review and make appriate checks in this reagrd before accepting any 
contribution. Adverse consequence may be in rejection or repeal of accepted submissions. Thus, 
contributors must make due deligence checks before submiting contibutions, with dependencies included.

#### 3.A. Open Software License v. 3.0 Compatiblity Chart

This is not an exhustive list, and may be subject to change without perior notice.

| Software | Artwork | 
| ------------- | ------------- |
| AFL  | Art Libre |
| Apache  | Artistic |
| BSD  | CC-0 |
| CC-O  | CC-BY |
| EPL  | CC-BY-SA |
| EUPL  | Unlicensed |
| ISC  | As such Public Domain is not acceptable |
| Unlicensed |  |

#### 3.B. Special Clauses
Incase dependencies might specify additional license clauses, that would introduce restriction of use, 
legal compliance must be verified before hand.

## 4. Developer Certification of Origin (DCO)

ActiveQuery has adopted OSL-3.0 license to strike a balance between open contributions besides allowing you 
to use the software however you would like to. Licensing is very important to open source projects, it tells 
you what rights you have and what rights copyright holder is providing. 

Nevertheless, spending time, effort and creativity to develope software that solves real world problems is one thing, 
but delivering that solution to masses is quite nother. Spanner in works comes when you need a law degree to do that. 

Instead of requiring to sing sophisticated Contributor License Agreement (CLA) or Corporate Contributor License Agreement 
(CCLA), ActiveQuery has adopted simpler [Developer Certificate of Origin (DCO)](DCO.md) Process introduced by the 
Linux Foundation as a [Contract by Conduct](https://www.upcounsel.com/acceptance-by-conduct-contract-law) 
provision.  

The DCO it self is an attestation attached to every contribution made by every developer. Whereby, the developer
intending to contribute simply adds a Signed-off-by statement in the commit message, regardless of channel of 
communication involved, and thereby through this very action agrees to the DCO. 

ActiveQuery Compliance Team closely reviews the Signed-off-by statement on each contribution and commit message. 
Abscence of which reaults in immediate of rejection. 

Further, details of DCO process are listed below.

## 4. Calender Versioning (CalVer)

ActiveQuery follows [CalVer scheme of semantic versioning](https://calver.org) and has adopted 
YYYY.MINOR.MICRO as  incremented version numbering format.

| CalVer Fromat  | Significance | Example |
| ------------- | ------------- | ------------- |
| YY  | Contarary to SemVer which uses arbitery numbering starting from 0 and incrimenting as 1,2,3 etc CalVer always uses year of release as first number for major segment numbering. | If release year is 2020 then YY indicates 20 |
| MINOR  | The second number referres to critical functionality releases as "breaking changes" starting from number 1 instead of 0. | 20.1 > 20.2 >> 20.5 |
| MICRO  | The third and usually final number referres to critical bugfix releases as "patch works" starting from number 1 instead of 0.  | 20.1.1 > 20.1.2 >> 20.2.13 |


When making breaking changes, we may also introduce deprecation warnings through MICRO version first so that 
users may learn about the upcoming changes and migrate their code base in advance. Change are documented in 
the CHANGELOG file placed at the root of each repository.

## Conventions
