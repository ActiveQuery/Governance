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

"ActiveQuery" is synonymous with and wheresoever referred to as "Active Query" or "ActiveQ" or "AQ", 
whether upper cased, lower cased or capitalised, and applies to all parts of ActiveQuery projects, 
programmes, repositories, and spaces. 

This guide presents preferred conventions but, most importantly describes as to why certain style 
rules take precedent?

ActiveQuery is group open source projects that are under very active development. Issues covered 
hereunder not only span to aesthetic issues of formatting or coding standards but other types of 
conventions or  as well. 

We looked around and picked the best of good practices and incorporated them into this document 
with the intention to keep community members on one page in adhering to hard-and-fast rules that 
ActiveQuery has universally adopted.


# 1. Branding

This perticular information is for wider generall awarness only. Branding including but not limited 
to characters, words, artworks, graphics, color schemes, slogans etc are copyrighted to and 
their use reserved to ActiveQuery.

**1.A** Letters **"aq"** in ActiveQuery graphical Logo will strictly use **Flat Case** as styling.

**1.B.** Wording **"ActiveQuery"** and will always use **Pascal Case**. However, this does not 
refute the probability where adoption is not possible e.g. in case of web url(s) or otherwise, then 
**Lisp Case** will be adopted as effective fall back, it is safe format for both filesystem and URL.

| Pascal Case | Lisp Case |
| ------------- | ------------- |
| /Governance  | /governance |
| /ActiveQuery  | /active-query |
| /active-query/ABRWillChangeToo/  | /active-query/abr-will-change-too |

**1.C.** Other than aforestated all other case formats are considered ineffective.



## 2. Action Vocabulary

Founding auther of ActiveQuery believe things are never good or bad persay, they are simply effective 
or ineffective to the cause. Therefore, ActiveQuery has done away the binary Yes/No, Acceptable/Unaccpetable 
format and has adopted more inclusive vocabulary.   

| Action | Impact |
| ------ | ------ |
| **Effective**  | Soemthing that has shown merit, and is always preffered. There would rarely be a case where one would need to break the convention. |
| **Reflect** | If you arrive at a point with good reason to deviate from the convention, then do so. Aim to be consistent, and before going forward do mitigate possible conflict at wider scope. |
| **Ineffective**  | Soemthing that has not shown merit, is never preffered and you should almost always avoid. |

## 3. Calendar Versioning (CalVer)

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

#### Specimen

|  Example  |  Action  |  Why  |
| ------------- | ------------- | ------------- |
| 20  | Ineffective | Use of YY on its own is meanginless. |
| 20.0  | Ineffective | MINOR must start from 1. |
| 20.1  | Reflect | Though it may seem reasonable to omit MICRO if its value is zero. It is not consistent with the adopted convention, having 20.1 (YY.MINOR) followed by 20.1.1 (YY.MINOR.MICRO) may be confusing and would certainly give rise to version parsing issues going forward. |
| -dito-|-dito- |If the case be that updates are of extremly low frequency or carry significant impact with only obvious/cosmatic changes as micro updates e.g. legal/information doucmentation then YY.MINOR may be considered post reflection. |
| 20.1.0  | Effective | Adhers to adopted YY.MINOR.MICRO convention. |

## 4. Naming Standards

ActiveQuery has standardised naming logic and apply to all parts of ActiveQuery projects, Programmes, repositories 
and spaces. 

ActiveQuery Compliance Team strictly enforces these naming standards, and adopting naming standards 
other than as stated against each sub-section of section 2 is not acceptable. 

Consequent may cause rejection of commit or repeal of previous submitted contributions. 

### 4.A File & Folder

ActiveQuery follows **Pascal Case** for naming all files and folders.

| File/Folder  | Pascal Case |
| ------------- | ------------- |
| file  | File |
| folder  | Folder |
| some folder/some file  | SomeFolder/SomeFile |
| ABBR remain unchanged  | ABBRRemainUnchanged |
| ABBR folder/ABBR file  | ABBRFolder/ABBRFile |

#### Specimen

| Example  | Action | Why |
| ------------- | ------------- | ------------- |
| PascalCase  | Effective | Conforms to prefered convention and will be consistent throughout.|
| lisp-case  | Reflect | Genrally safe for URLs but in some cases may require path encoding. |
| snake_case  | Reflect | Genrally safe for filesystem but is an obsolete URL trend and in some cases may require path encoding. |
| flat case  | Ineffective | Error prone. |
| UPPER FLAT CASE  | Ineffective | Error prone. |
| dot.case  | Ineffective | Error Prone,  always avoided and rarely supported in by filesystem or URL parsers.|
| SCREAMING_SNAKE_CASE  | Ineffective | Reserved format for naming core legal/information documents. Error prone, obsolete trend and harder for general public to follow. |
| dromedaryCase  | Ineffective | Error prone, almost nevre adopted and harder for general public to follow.  |
| camel_Snake_Case  | Ineffective | Error prone, almost nevre adopted and harder for general public to follow. |
| SCREAMING-LISP-CASE  | Ineffective | Error prone, obsolete trend and harder for general public to follow. |
| Train-Case  | Ineffective |Error prone, almost nevre adopted and harder for general public to follow. |

### 4.B. Legal & Information Documentation 

ActiveQuery follows **Screaming Snake Case** for naming all ledgal and information realted documentation files.

| File | Screaming Snake Case |
| ------------- | ------------- |
| readme  | README |
| ABBR  | ABBR |
| some file  | SOME_FILE |

### 4.C. JavaScript (JS) & PHP

**4.C.i.** ActiveQuery uses **Dromedary Case** for naming JS & PHP Objects.

| Objects | Dromedary Case |
| ------------- | ------------- |
| my  | my |
| myfunction  | myFunction |
| myobject  | myObject |
| myobjectname  | myObjectName |

**4.C.ii.** ActiveQuery uses **Pascal Case** for naming JS & PHP Classes.

| Classes | Pascal Case |
| ------------- | ------------- |
| my  | My |
| myclass  | MyClass |
| myconstantname  | MyConstantName |

**4.C.iii.** ActiveQuery uses **Pascal Case** for naming PHP Namespaces.

| Namespace | Pascal Case |
| ------------- | ------------- |
| my  | My |
| mynamespace  | MyNameSpace |


### 4.D. Cascading Style Sheet (CSS)

ActiveQuery follows **Lisp Case** for naming all CSS Classes and Variables.

| CSS Classes/Variables | Lisp Case |
| ------------- | ------------- |
| my  | my |
| my class  | my-class |
| my variable | --my-variable |

## 5. Directory Structure

### 5.A. Repository Essential Files 

```
root/
├── CODE_OF_CONDUCT_POLICY
├── CONTRIBUTION_POLICY
├── ETHICAL_POLICY
├── DCO
├── CHANGE_LOG
├── LICENSE
├── RepositoryEntryFile
└── README.md
```

### 5.B. Repository Sub-Directories 

```
root/
├── REPOSITORY_ESSENTIAL_FILES
├── RepositoryEntryFile
└── AQStream  
   │──── Quarks
   │      ├── CoreComponentA
   │      │     └── Files/Folders
   │      ├── CoreComponentB
   │      │     └── Files/Folders
   │      └── CoreComponentGroup
   │              ├── SubComponentA
   │              │     └── Files/Folders
   │              └── SubComponentB
   │                    └── Files/Folders
   └── Lepton
       ├── CorePluginA
       │    └── Files/Folders
       ├── CorePluginGroup
       │      ├── SubPluginA
       │      │     └── Files/Folders
       │      └── SubPluginB
       │            └── Files/Folders
       └── CorePluginB
            └── Files/Folders

```


### 5.C. MarketSpace 

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


