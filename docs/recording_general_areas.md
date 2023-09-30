---
layout: default
title: Recording General Areas
nav_order: 7
---

# Recording General Areas
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

General area nodes are a unique addition to the China Historical Database (CHCD) which allows the database to capture a person’s location when they were not affiliated with a particular institution or event. In order to simplify the geographic system and keep from recording duplicate data, people can not have a direct relationship with a geographic node. Instead, a person receives geographic information through connections with institutions, events and general areas .

This documentation provides guidelines to help you format your own data collection sheets so that the data can be readily cleaned and inputted into the CHCD. Each section provides a description of what is being recorded, a general format for how to record, and examples.

### Defining a General Area in the CHCD.
In the CHCD, a *general area* is defined as a region in China without any specific institutional or corporate affiliation. General Areas can be created at any level of geographic specificity in the database, including counties, prefectures, and provinces. 

General Areas serve the same purpose as placeholder institutions in version 1 of the CHCD. Beginning with version 2, placeholder institutions were eliminated and the general area node type was added for greater clarity and ease of use. 

>*Note: These general formats are suggestions for use in your own data collection, however, please refer to [Data Collection Basics](/data-collection/docs/data_collection_basics/) before designing your own spreadsheets.*

---

## Identifying Static Properties
These are general properties which are recorded non-relationally in the database. They are *identifying* because they are generally unique to each general area.

Below is a list of identifying static properties which should be recorded if your historical document contains them.

---

### name_western
All general areas are named according to the location they represent. The location’s name should be given in the current English equivalent of the modern Chinese geographic term for the place. 

#### FORMAT
{: .no_toc }
```
General Area (Location) 
```
#### EXAMPLES
{: .no_toc }
```
General Area (Beijing)
General Area (Guangzhou) 
```
---

### alternative_name_western
Alternative names in English or other Western (e.g. Latin, Dutch, etc.). List common spellings and alternate names for the location that the general area represents. If listing more than one name, use a semicolon to separate the entries. Separate the names by a semicolon.

#### FORMAT
{: .no_toc }
```
Alternative Name; Alternative Name; ...
```
#### EXAMPLES
{: .no_toc }
```
Nankin; Nanking 
Kunming; Yunnanfu 
Eastern Setchoan
```
---

## Relationships
General Area nodes can have two kinds of relationships in the CHCD:
- [**LOCATED_IN**](#located_in): This links General Area nodes to Geography nodes.
- [**PRESENT_AT**](#present_at): This links Person nodes to General Area nodes.

These two categories are devised so as to offer a range of flexibility in recording different types of relationships, while also providing a framework to organize them. When designing your spreadsheet and recording data, it is good to keep these basic relationships in mind. Below are descriptions of each relationships and an example of how it  might be recorded in a spreadsheet.

---

### LOCATED_IN
This relationship is among the most important in the database and connects an institution, general area, or event to a geography node. More colloquially, this is how the database records the location of an event or institution. In the database, this relationship enables these nodes (and people who are connected to them) to be connected to geographic coordinates.

This relationship also has its own properties which can be used to record data about the nature of the relationship. They are as follows:
- `start_year` : Records the starting year of the relationship, also used if no end date to the relationship is available.
- `start_month` : Records the starting month of the relationship, also used if no end date to the relationship is available.
- `start_day` : Records the starting day of the relationship, also used if no end date to the relationship is available.
- `end_year` : Records the ending year of the relationship.
- `end_month` : Records the ending year of the relationship.
- `end_day` : Records the ending year of the relationship.
- `note` : Records any additional information about the relationship.
- `source` : Records the source in which the relationship is attested.

#### NOTE ON COLLECTING LOCATED_IN RELATIONSHIPS
{: .no_toc }
Historical locations in China can, at times, be difficult to locate depending on the nature of the source and the location in question. Various romanization systems, shifting administrative divisions, and changing names can make locating historical sources difficult. For this reason, the CHCD has chosen to always record the place name as listed in a historical source.

At the same time, the CHCD uses a [Geography System](/data-collection/docs/geography) that corresponds to a modern administrative map of China. While limited, this use of the multi-level geography system allows us to capture historical geographic data that is precise to varying degrees. As such, when collecting data, it is a best practice to relate the historic location to its most specific modern equivalent and include the corresponding CHCD geography code.


#### EXAMPLE HEADER FORMAT
{: .no_toc }
```
Institution; Historic Place Name; Modern Location; Geocode
```
#### EXAMPLE ENTRIES
{: .no_toc }
```
Chefoo Mission for the Blind; Zhifu District, Yantai; C1497
Church of the Savior; Peking; Xicheng District, Beijing; C2513
```
---

### PRESENT_AT
This relationship category is used to connect People to Institutions, General Areas and Events, and thus to record where they were located in China (see note below).

This relationship also has its own properties which can be used to record data about the nature of the relationship. They are as follows:
- `relationship_type` : A one or two word descriptor of the person's relationship to the institution or event.
- `start_year` : Records the starting year of the relationship, also used if no end date to the relationship is available.
- `start_month` : Records the starting month of the relationship, also used if no end date to the relationship is available.
- `start_day` : Records the starting day of the relationship, also used if no end date to the relationship is available.
- `end_year` : Records the ending year of the relationship.
- `end_month` : Records the ending year of the relationship.
- `end_day` : Records the ending year of the relationship.
- `note` : Records any additional information about the relationship.
- `source` : Records the source in which the relationship is attested.

#### NOTE ON COLLECTING PRESENT_AT RELATIONSHIPS
{: .no_toc }

As historical sources may not include all of this data, it is important to adapt one's spreadsheet to fit the nature of the source for the sake of efficiency. When entering data, make it clear in table headings which kind of data is being collected in the column.

Please remember, in the CHCD, geography is controlled by allowing only institutions and events to have geographic locations (For more on this design choice, see [Database Design](/data-collection/docs/database_design/) and [Geography]/data-collection/docs/geography/). As such, persons are not directly linked to geographic nodes in the database. Due to this, one should use placeholder institutions when a person is present in a location, but is not institutionally affiliated. For more on the correct formatting of placeholder institutions, see [Placeholder Institutions](/data-collection/docs/geography/#placeholder-institutions).

#### EXAMPLE HEADER FORMAT
{: .no_toc }
```
Institution; Start YYYY; Relationship Type; Recorded Place Name; Modern Place Name; Geography Code; Note
```
#### EXAMPLE ENTRIES
{: .no_toc }
```
Jesuit College of Macao; 1921; Guest; Macau; Macao; C979; Worked as pharmacist while present.
General Area (Shanxi); 1933; Evangelist; Shansi; Shanxi; C979;
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
