---
layout: default
title: Recording Publications
nav_order: 8
---

# Recording Publications
{: .no_toc }

<details open markdown="block">
  <summary>
    Table of contents
  </summary>
  {: .text-delta }
1. TOC
{:toc}
</details>
---

## Introduction

Publication nodes were added to the CHCD in version 2. They are used to record information about books, journals, posters, calendars, tracks, and other types of publications. Publications in the CHCD are either works published in China about Christianity or works published outside of China about Christianity in China. 

This documentation provides guidelines to help you format your own data collection sheets so that the data can be readily cleaned and inputted into the CHCD. Each section provides a description of what is being recorded, a general format for how to record, and examples.

>*Note: These general formats are suggestions for use in your own data collection, however, please refer to [Data Collection Basics](/data-collection/docs/data_collection_basics/) before designing your own spreadsheets.*

---

## Identifying Static Properties
These are general properties which are recorded non-relationally in the database. They are *identifying* because they are generally unique to each institution.

Below is a list of identifying static properties which should be recorded if your historical document contains them.

---

### name_western
The official or most common English title of the publication or a reasonable English translation. If a publication was published in a Western language other than English, please list an English translation for the title in this field. 
#### FORMAT
{: .no_toc }
```
Publication Title
```
#### EXAMPLES
{: .no_toc }
```
Monthly of the Catholic Action
The Manchu-Knoller
```
---

### alternative_name_western
Alternate titles of the publication in other Western languages (e.g. Latin, Dutch, etc.). List common spellings and alternate titles that the publication is recorded under. If listing more than one title, use a semicolon to separate the entries. Separate the names by a semicolon.

#### FORMAT
{: .no_toc }
```
Alternative Title; Alternative Title; ...
```
#### EXAMPLES
{: .no_toc }
```
Ruch Chrześcijańsko-Spoleczny
"Bulletin Catholique" de l'Eparchie russe du rite byz-slave en Manchurie; Католицький бюлетень Російської єпархії визько-слов'янського обряду в Маньчжурії;
```
---
### chinese_name_romanized
Chinese title of the publication in Romanized script, pinyin first followed by any other spelling system. Alternative spellings with a semicolon. Designate the romanization system by abbreviation when possible.

Here is a list of the most common romanization systems utilized with suggested abbreviation:

- *(py)*: Hanyu pinyin
- *(wg)*: Wade-Giles
- *(y)*: Yale
- *(lsw)*: Latinhua Sin Wenz
- *(gr)*: Gwoyeu Romatzyh (National Romanization)
- *(j2)*: Juyin II
- *(po)*: Chinese Post Office System
- *(rt)*: Ricci-Trigault System
- *(ef)*: Système de l'École Française d'Extrême-Orient

#### FORMAT
{: .no_toc }
```
Title (system); Title (system); ...
```
#### EXAMPLES
{: .no_toc }
```
San I Shêng (unknown)
Ma Na (py)
```
---

### chinese_alternative_name_romanized
Alternate Chinese titles, including different spellings, under which the publication is recorded. If listing more than one name, use a semicolon to separate the entries. Designate the romanization system by abbreviation when possible.

Here is a list of the most common romanization systems utilized with suggested abbreviation:

- *(py)*: Hanyu pinyin
- *(wg)*: Wade-Giles
- *(y)*: Yale
- *(lsw)*: Latinhua Sin Wenz
- *(gr)*: Gwoyeu Romatzyh (National Romanization)
- *(j2)*: Juyin II
- *(po)*: Chinese Post Office System
- *(rt)*: Ricci-Trigault System
- *(ef)*: Système de l'École Française d'Extrême-Orient

#### FORMAT
{: .no_toc }
```
Alternative Title (system); Alternative Title (system);
```
#### EXAMPLE
{: .no_toc }
```
De guo mang ren zhi jia (py)
Bei tang (py); Xi shen ku tian zhu tang (py); hsi shih k'u t'ien chu t'ang (wg)
```
---

### chinese_name_hanzi
The most official or most common Chinese title of the publication, typed in *traditional* (i.e. non-simplified) characters [繁體字].

#### FORMAT
{: .no_toc }
```
出版品名稱
```
#### EXAMPLES
{: .no_toc }
```
華東教育
東聲
```
---

### chinese_alternative_name_hanzi
Alternate Chinese titles used by the publication. Alternate names should be types in *traditional* (i.e. non-simplified) characters.

#### FORMAT
{: .no_toc }
```
出版品名稱; 出版品名稱; ...
```
#### EXAMPLE
{: .no_toc }
```
新生命
之江校刊; 之江學報
```
---

### start_date
List the start date of the publication using the Gregorian calendar in this order, separated by semicolon: day; month; year. If only a Chinese lunar calendar date is available to you, use a [calendrical concordance](https://sinocal.sinica.edu.tw/) to convert it to the Gregorian calendar. 

>*Note: If the publication is not a series (i.e. a book), this field simply records the publication date.
>*Note: If only a year or month is available, you may leave off more specific date components.

#### FORMAT
{: .no_toc }
```
YYYY; MM; DD
```
#### EXAMPLES
{: .no_toc }
```
1909; 05
1703; 02; 09
```
---

### end_date
List the end date of the publication using the Gregorian calendar in this order, separated by semicolon: day; month; year. If only a Chinese lunar calendar date is available to you, use a [calendrical concordance](https://sinocal.sinica.edu.tw/) to convert it to the Gregorian calendar.

>*Note: If only a year or month is available, you may leave off more specific date components. If the publication is still in existence and in use, you use the value "active" to denote its continuing presence.

#### FORMAT
{: .no_toc }
```
YYYY; MM; DD
```
#### EXAMPLES
{: .no_toc }
```
1936
active
```
---

### edition
List the edition of the publication. This will typically be used when recording a book that has been released in multiple editions. 

>*Note: Record this field using a number whenever possible.

#### FORMAT
{: .no_toc }
```
edition
```
#### EXAMPLES
{: .no_toc }
```
1
2
```
---

### volume_number
List the volume number of the publication. The volume number typically counts how many years a publication has been running.

>*Note: Record this field using a number whenever possible.

#### FORMAT
{: .no_toc }
```
volume
```
#### EXAMPLES
{: .no_toc }
```
1
2
```
---

### issue_number
List the issue number of the publication. The issue number typically counts how many times a publication has been released in a given year.

>*Note: Record this field using a number whenever possible.

#### FORMAT
{: .no_toc }
```
issue
```
#### EXAMPLES
{: .no_toc }
```
1
2
```
---

### issue_frequency
Record how frequently the publication is released. Please use a conscise description

#### FORMAT
{: .no_toc }
```
issue frequnecy
```
#### EXAMPLES
{: .no_toc }
```
Every other year
Bi-annually
Monthly
```
---

### circulation
Circulation is a count of how many copies of a particular publication are distributed.

#### FORMAT
{: .no_toc }
```
circulation
```
#### EXAMPLES
{: .no_toc }
```
5,000
500 (320 abroad)
```
---

### format
Record information about the format of the publication. This could include information about the physical size of the publication, the medium it was printed on, the number of pages, or other information. Record this information as succinctly as possible.

#### FORMAT
{: .no_toc }
```
description of the format
```
#### EXAMPLES
{: .no_toc }
```
21x15, 80 pages
from 26x19 to 23x16, 40-60 pages
```
---

### price
Record information about the price of the publication. This could include information about the price of a single copy, a yearly subscription, or other pricing information. Record this information as succinctly as possible.

#### FORMAT
{: .no_toc }
```
Price (situation); Price (situation);...
```
#### EXAMPLES
{: .no_toc }
```
Free
$2 (yearly subscription in China); 2 gobi (yearly subscription in Manchuria); $2 (yearly subscription in US); 20 cents (per issue)
5 cents (per issue); 60 cents (yearly subscription)
```
---

### publication_language
Record the original language(s) of the publication. If the publication included multiple languages, separate them by a semicolon. If a given publication was issued in multiple languages, please create a new publication node for each language.

#### FORMAT
{: .no_toc }
```
Language; Language…
```
#### EXAMPLES
{: .no_toc }
```
English
Chinese (simplified)
Chinese (文言文); Japanese
```
---

### publication_category
This property records the primary type of the publication. These properties are a set list, but more specific categorization can be achieved with the [publication_subcategory](#publication_subcategory) property.  

Currently, this property has five potential values:
- **Book**: Used for a book, pamphlet, or other stand-alone publication
- **Series**: Used for journals, magazines, newspapers, etc.
- **Issue**: Used for a specific issue of a journal, magazine, newspaper, etc.
- **Ephemera**: Used for posters, calendars, tracks, maps, etc.
- **Other**: Used for any other miscellaneous types of publication.

#### FORMAT
{: .no_toc }
```
Type
```
#### EXAMPLES
{: .no_toc }
```
Book
Series
```
---

### publication_subcategory
This property records the specific type of the publication being recorded. There is not currently a set list of values, but it is best practice to follow the descriptors of historical documents. If multiple subcategories can be used, separate them using a semicolon.

#### FORMAT
{: .no_toc }
```
Subcategory; Subcategory; ...
```
#### EXAMPLES
{: .no_toc }
```
Children’s paper
Theological news; mission news
```
---

## Documentational Static Properties
These are documentational properties which are recorded non-relationally in the database. They are *documentational* because they record additional notes and source material.

Below is a list of documentational static properties which should be recorded if your historical document contains them.

---

### notes
Add any additional pertinent information that cannot be recorded any of the other static categories. There is no standardized format for this property.

#### FORMAT
{: .no_toc }
```
No set format.
```
#### EXAMPLE
{: .no_toc }
```
Occasionally funded by grants from German government.
Suspended for a year, afterwards continued under the title of The Ringing Bell
```
---

### source
List the sources where the information in this table has been found, followed by page number in parenthesis. Indicate first major reference sources used, then more focused sources if some specific information is not in main reference sources (indicate what). Sources can be indicated in abbreviated form or with acronyms (e.g *Dehergne Repertoire*, 159).

#### FORMAT
{: .no_toc }
```
Source Information [Page #]; Source Information [Page #];
```
#### EXAMPLE
{: .no_toc }
```
Eugenio Menegon, “Ricci, Francesco,” in  Dizionario biografico degli Italiani, vol X, Roma, Istituto Treccani, 2016 [XX]; For name in Chinese see ARSI, Japonica Sinica XXX [XX]
```
---

## Relationships
Publication nodes can have one kind of relationships in the CHCD:
- [**INVOLVED_WITH**](#involved_with): This relationship category is used to connect Publications to People, Institutions, Corporate Entities, Events, General Areas, or other Publications. 

When designing your spreadsheet and recording data, it is good to keep these basic relationships in mind. Below are descriptions of each relationships and an example of how it  might be recorded in a spreadsheet.

---

### INVOLVED_WITH
This relationship category is used to connect Publications to People, Institutions, Corporate Entities, Events, General Areas, or other Publications. 

This relationship also has its own properties which can be used to record data about the nature of the relationship. They are as follows:
- `relationship_type` : A one or two word descriptor of the node’s relationship to the publication.
- `start_year` : Records the starting year of the relationship, also used if no end date to the relationship is available.
- `start_month` : Records the starting month of the relationship, also used if no end date to the relationship is available.
- `start_day` : Records the starting day of the relationship, also used if no end date to the relationship is available.
- `end_year` : Records the ending year of the relationship.
- `end_month` : Records the ending year of the relationship.
- `end_day` : Records the ending year of the relationship.
- `note` : Records any additional information about the relationship.
- `source `: Records the source in which the relationship is attested.

#### NOTE ON COLLECTING INVOLVED_WITH RELATIONSHIPS
{: .no_toc }

This relationship type is designed to allow for flexibility when linking other nodes to publications. Therefore, the relationship_type property of the relationship is important for providing more detail about the nature of the connection. Below are some examples of possible relationship types between nodes (this list is not exhaustive):
- `Person` -> `Publication`: editor, author, contributor, subscriber, reader
- `Institution` -> `Publication`: published, funded, commissioned, supported
- `CorporateEntity` -> `Publication`: published, funded, commissioned, supported 
- `Event` -> `Publication`: recorded in, promoted, distributed at
- `Publication` -> `General Area`: published in  
- `Publication` -> `Publication`: second edition, sequel, part of, issue of, responding to

#### EXAMPLE HEADER FORMAT
{: .no_toc }
```
Publication; Start YYYY; End YYYY; Relationship Type; Geography Code; Note
```

#### EXAMPLE ENTRIES
{: .no_toc }
```
Monumenta Serica; 1921; 1930; Co-editor; Was the founding editor.
The Chinese Recorder; 1885; Issue of; sixteenth volume;
```
---

## Example Spreadsheets
As stated throughout, make sure to design your spreadsheet to work most efficiently with your source materials. That said, it can be helpful to see examples of spreadsheets in action.

### SPREADSHEET 1: SINGLE PERSON RESEACH
{: .no_toc }
This sort of spreadsheet might be useful if you are inputting data from a personal archive or biography.

[Spreadsheet 1](https://docs.google.com/spreadsheets/d/10BuoT-fsqqMzPzTqRK-T_U4nrzBxgcirkVBls2bBFvw/edit?usp=sharing){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }

### SPREADSHEET 2: MULTI-PERSON RESEARCH
{: .no_toc }
This sort of spreadsheet might be useful if you are working through a institutional archive, necrology, or specialized directory.

[Spreadsheet 2](https://docs.google.com/spreadsheets/d/1Z-Buq3Hjz9y0sQziInQlaaauqSWTJWWu0j2BC4YW_WI/edit?usp=sharing){: .btn .btn-primary .fs-5 .mb-4 .mb-md-0 .mr-2 }
