---
layout: default
title: Recording People
nav_order: 4
---

# Recording People
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

People are the most numerous kind of node in the China Historical Database (CHCD). As such, the database has numerous properties which can be used to record information about people. This documentation provides guidelines to help you format your own data collection sheets so that the data can be readily cleaned and inputted into the CHCD.

Most of these properties cannot be conceptualized as a relationships. However, the CHCD team chose to record a select number of properties as static which could have been otherwise recorded. This choice was due to ensure that future queries of the data did not become too complex or worse, unmeaningful.

Each section provides a description of what is being recorded, a general format for how to record, and examples.

*Note: These general formats are suggestions for use in your own data collection, however, please refer to [Data Collection Basics](/docs/data_collection_basics/) before designing your own spreadsheets.*

---

## Identifying Static Properties
These are general properties which are recorded non-relationally in the database. They are *identifying* because they refer primarily to a person's personal identity and life-events.

Below is a list of identifying static properties which should be recorded if your historical document contains them.

---
### FAMILY_NAME_WESTERN
Western language family name; in the native language of the individual, if possible.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### GIVEN_NAME_WESTERN
Western language given name(s); in the native language of the individual, if possible. For individuals with multiple names, use the name given at birth, if possible. If the birth name is not available, use the most well known name.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### ALTERNATIVE_NAME_WESTERN
Alternate names in other Western languages (e.g. Latin, Dutch, etc.). List common spellings and alternate names that the individual is recorded under.  If listing more than one name, use a semicolon to separate the entries.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
### CHINESE_FAMILY_NAME_ROMANIZED
Chinese family name in Romanized script, pinyin first followed by any other spelling system. Separate the names by a semicolon.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### CHINESE_GIVEN_NAME_ROMANIZED
Chinese given name in Romanized script, pinyin first followed by any other spelling system. Separate the names by a semicolon.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### CHINESE_ALTERNATE_NAME_ROMANIZED
Alternate Chinese names, including different spellings, that the individual is recorded under. If listing more than one name, use a semicolon to separate the entries.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### CHINESE_FAMILY_NAME_HANZI
The family name [姓] of an individual, typed in *traditional* (i.e. non-simplified) characters [繁體字].

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### CHINESE_GIVEN_NAME_HANZI
The given name [名] of an individual, typed in *traditional* (i.e. non-simplified) characters [繁體字].

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### CHINESE_ALTERNATIVE_NAME_HANZI
Include any zi [字] or hao [號]，or other Chinese alternate names utilized by the individual, followed by the type in parenthesis. Alternate names should be types in *traditional* (i.e. non-simplified) characters, and *pinyin* should be used to record the type.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### GENDER
Use the following notation to record the gender of an individual: M = Male; F = Female; U = Unknown; N = Non-binary
---
### NATIONALITY
List the modern nation-state which occupies the same geography as the birthplace of the individual. Record in English.
---
### BIRTH_DATE
List the date of birth.

#### FORMAT
{: .no_toc }
```
YYYY; MM; DD
```
#### EXAMPLE
{: .no_toc }
```
1917; 02; 13
```
---
### BIRTH_PLACE
List the place of birth. The name of the place is recorded in its original language, as well as its modern equivalent. If the location is in China, a [Geography Code](/docs/geography) is added.

#### FORMAT
{: .no_toc }
```
Original Place Name; Modern Place Name; Geography Code
```
#### EXAMPLE
{: .no_toc }
```
Firenze; Florence; --
```
---
### DEATH_DATE
List the date of death.

#### FORMAT
{: .no_toc }
```
YYYY; MM; DD
```
#### EXAMPLE
{: .no_toc }
```
1917; 02; 13
```
---
### DEATH_PLACE
List the place of death. The name of the place is recorded in its original language, as well as its modern equivalent. If the location is in China, a [Geography Code](/docs/geography) is added.

#### FORMAT
{: .no_toc }
```
Original Place Name; Modern Place Name; Geography Code
```
#### EXAMPLE
{: .no_toc }
```
Firenze; Florence; --
```
---

## Descriptive Static Properties
These are descriptive properties which are recorded non-relationally in the database. They are *descriptive* because they refer primarily to a affiliations and accomplishments of the person.

Below is a list of descriptive static properties which should be recorded if your historical document contains them.

---

### CHRISTIAN_TRADITION
List the tradition to which this individual belongs. Use the following notation: P = Protestant; C =Catholic; X = Orthodox.
---
### RELIGIOUS_FAMILY
List the general Christian family this person belongs to. For Protestants this includes groupings such as: Lutheran, Methodist, Baptist etc.; for Catholics, this includes groupings within a common general tradition or rule such as: Augustinian, Benedictine, Franciscan (these large ‘regular’ orders were often composed of subgroups, e.g. Discalced Augustinians; Observant or Reformed Friars Minor / Franciscans; etc.). If they belong to more than one tradition, separate by semicolon.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### RELIGIOUS_BODY
List the specific religious group to which the person belonged. for Protestants this indicates the specific denomination, missionary body, or sending agency (e.g. the Church Missionary Society, the True Jesus Church, etc.). For Catholics and Orthodox, this indicates the specific religious order or sending agency, such as Discalced Carmelites; Jesuits; Dominicans, Propaganda Fide etc.)

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### DEGREES_HELD
Western state degrees, church degrees, or Chinese examination degrees, , followed by the year in which they received the title, if known. If listing more than one degree, use a semicolon to separate the entries.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### TITLES
List all honorary and ecclesial titles obtained by individuals throughout their careers, followed by the year in which they received the title, if known. If listing more than one title, use a semicolon to separate the entries.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### CATHOLIC EXAMPLE
{: .no_toc }
```
This is a code box
```
#### PROTESTANT EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### JOBS
Occupations held during their time in China. These are not typically linked to a specific place. If they are, see the [Location](#location) relationship. Provide dates, if available, and separate by semicolon if there are more than one jobs.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---

## Catholic-Specific Static Properties
These are properties which are recorded non-relationally in the database. They are *Catholic-specific* because they typically only used by Catholic individuals.

Below is a list of Catholic-specific static properties which should be recorded if your historical document contains them.

---
### BAPTISMAL_NAME_WESTERN
Mainly used for Chinese converts and members of religious orders. If listing more than one name, use a semicolon to separate the entries.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### CHINESE_BAPTISMAL_NAME_ROMANIZED
Mainly used for Chinese converts. If listing more than one name, use a semicolon to separate the entries.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### CHINESE_BAPTISMAL_NAME_HANZI
The baptismal name [洗名] of an individual, typed in *traditional* (i.e. non-simplified) characters [繁體字].

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### ORIGINATING_PROVINCE
List the religious province to which the person belonged prior to their arrival in China.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### CHINA_PROVINCE
List the religious province to which the person belonged during their time in China.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### JOIN_DATE
List the date in which the person joined the order or congregation.

#### FORMAT
{: .no_toc }
```
YYYY; MM; DD
```
#### EXAMPLE
{: .no_toc }
```
1783; 02; --
```
---
### VOWS
List the vows which the person took and dates, if available. Vows should be seperated by semicolons.

#### FORMAT
{: .no_toc }
```
YYYY; MM; DD
```
#### EXAMPLE
{: .no_toc }
```
1783; 02; --
```
---

## Documentational Static Properties
These are documentational properties which are recorded non-relationally in the database. They are *documentational* because they record additional notes and source material.

Below is a list of documentational static properties which should be recorded if your historical document contains them.

---
### NOTES
Add any additional pertinent information that cannot be recorded any of the other static categories. There is no standardized format for this property.
---
### SOURCE
List the sources where the information in this table has been found, followed by page number after a comma. Indicate first major reference sources used, then more focused sources if some specific information is not in main reference sources (indicate what). Sources can be indicated in abbreviated form or with acronyms (e.g Dehergne Repertoire, 159).
---

## Relationships
These are relationships which are typically held by individuals in the database. Once entered into the database, these will become edges that connect the various nodes.

Below is a list of relationships which should be recorded for a person if your historical document contains them.

---
### LOCATION
To be added.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### MARRIAGE_WESTERN
To be added.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### MARRIAGE_ROMANIZED
To be added.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### MARRIAGE_HANZI
To be added.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### OFFSPRING_WESTERN
To be added.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### OFFSPRING_ROMANIZED
To be added.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
### OFFSPRING_HANZI
To be added.

#### FORMAT
{: .no_toc }
```
This is a code box
```
#### EXAMPLE
{: .no_toc }
```
This is a code box
```
---
