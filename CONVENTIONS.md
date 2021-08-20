# ActiveQuery Conventions v21.1

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

ActiveQuery (synonymous with and wheresoever referred to as "Active Query" or "ActiveQ" or "AQ", 
whether upper cased, lower cased or capitalised) and applies to all parts of ActiveQuery projects, 
programmes, repositories, and spaces. 

ActiveQuery is group open source projects that are under very active development. 
There's always more to be done and we are always working on making contributing to 
projects as easy, inclusive and transparent as possible. ActiveQuery welcomes anyone 
willing to put in the time and effort to help us and our community of users.

This document will help answer common questions that you may have.

## 1. Calendar Versioning (CalVer)

ActiveQuery follows [CalVer scheme of semantic versioning](https://calver.org) and has adopted 
**YY.MINOR.MICRO** as incremented version numbering format.

| CalVer Format  | Significance | Example |
| ------------- | ------------- | ------------- |
| YY  | Contrary to SemVer which uses arbitrary numbering starting from 0 and incrementing as 1,2,3 etc CalVer always uses year of release as first number for major segment numbering. | If release year is 2020 then YY indicates 20 |
| MINOR  | The second number refers to critical functionality releases as "breaking changes" starting from number 1 instead of 0. | 20.1 > 20.2 >> 20.5 |
| MICRO  | The third and usually final number refers to critical bugfix releases as "patch works".  | 20.1.0 > 20.1.1 >> 20.2.13 |

When making breaking changes, we may also introduce deprecation warnings through MICRO version first so that 
users may learn about the upcoming changes and migrate their code base in advance. Change are documented in 
the CHANGELOG file placed at the root of each repository.

## 2. Naming Standards

ActiveQuery has standardised naming logic and apply to all parts of ActiveQuery projects, Programmes, repositories 
and spaces. 

ActiveQuery Compliance Team strictly enforces these naming standards, and adopting naming standards 
other than as stated against each sub-section of section 2 is not acceptable. 

Consequent may cause rejection of commit or repeal of previous submitted contributions. 

### 2.A. Branding

**5.B.1.i.** ActiveQuery (synonymous with "Active Query" and wheresoever abbreviated as "ActiveQ" 
or "AQ", whether upper cased, lower cased or capitalised) branding will always follow 
**Pascal Case**. 

However, this does not refute the probability where adoption is not possible e.g. in case of web url(s)
or otherwise, then **Kebab Case** will be adopted as fallback.

| Pascal Case | Kebab Case |
| ------------- | ------------- |
| /Governance  | /governance |
| /ActiveQuery  | /active-query |
| /active-query/ABRReaminUnchanged/  | /active-query/ABR-reamin-unchanged |

**5.B.1.ii.** Letters **"aq"** in ActiveQuery graphical Logo will strictly use **Lower Case** as styling.

### 2.B File & Folder

ActiveQuery follows **Pascal Case** for naming all files and folders.

| File/Folder  | Pascal Case |
| ------------- | ------------- |
| file  | File |
| folder  | Folder |
| some folder/some file  | SomeFolder/SomeFile |
| ABBR remain unchanged  | ABBRRemainUnchanged |
| ABBR folder/ABBR file  | ABBRFolder/ABBRFile |

### 2.C. Legal Documentation 

ActiveQuery follows **Screaming Snake Case** for naming all ledgal documentation files.

| File | Screaming Snake Case |
| ------------- | ------------- |
| readme  | README |
| ABBR  | ABBR |
| some file  | SOME_FILE |

### 2.D. JavaScript (JS)

**2.D.i.** ActiveQuery follows **Dromedary Case** for naming all JS Objects.

| JS Objects | Dromedary Case |
| ------------- | ------------- |
| my  | my |
| myfunction  | myFunction |
| myobject  | myObject |
| myobjectname  | myObjectName |

**2.D.ii.** ActiveQuery follows **Pascal Case** for naming all JS Classes.

| JS Classes | Pascal Case |
| ------------- | ------------- |
| my  | My |
| myclass  | MyClass |
| myconstantname  | MyConstantName |

### 2.E. Cascading Style Sheet (CSS)

ActiveQuery follows **Kebab Case** for naming all CSS Classes and Variables.

| CSS Classes/Variables | Kebab Case |
| ------------- | ------------- |
| my  | my |
| my class  | my-class |
| my variable | --my-variable |

### 2.F. Directory Structure

```
root/
├── CODE_OF_CONDUCT_POLICY
├── CONTRIBUTION_POLICY
├── ETHICAL_POLICY
├── DCO
├── CHANGE_LOG
├── LICENSE
└── README.md
```

```
root/
├── CODE_OF_CONDUCT_POLICY
├── CONTRIBUTION_POLICY
├── ETHICAL_POLICY
├── DCO
├── CHANGE_LOG
├── LICENSE
├── README.md
├── FrameworkEntryFile
└── AQStream
   │   └── Quarks
   │        ├── CoreComponentA
   │        │     └── Files/Folders
   │        ├── CoreComponentB
   │        │     └── Files/Folders
   │        └── CoreComponentGroup
   │              ├── SubCatagoryA
   │              │     └── Files/Folders
   │              └── SubCatagoryB
   │                    └── Files/Folders
   └── Lepton
       ├── CorePluginA
       │    └── Files/Folders
       ├── CorePluginGroup
       │      ├── SubCatagoryA
       │      │     └── Files/Folders
       │      └── SubCatagoryB
       │            └── Files/Folders
       └── CorePluginB
            └── Files/Folders

```
```
marketplace/
├── CODE_OF_CONDUCT_POLICY
├── CONTRIBUTION_POLICY
├── ETHICAL_POLICY
├── DCO
├── CHANGE_LOG
├── LICENSE
├── README.md
├── FrameworkEntryFile
├── CustomPluginA
│    └── Files/Folders
├── CustomPluginGroup
│      ├── SubCatagoryA
│      │     └── Files/Folders
│      └── SubCatagoryB
│            └── Files/Folders
└── CustomPluginB
       └── Files/Folders

```
