---
sectionid: preparing-datasets
sectionclass: h3
parent-id: publishing-data
title: Preparing the Datasets
number: 4120
---

In order to prepare data sets to maximize their usefulness, it's important to acknowledge the different types of formats available as well as the limitations that they may present:

||| **Tabular**                |
| File Type   | Openness | Notes |
| ----------- | :------: | :---: |
| CSV         | High     | A versatile format for opening structured data (eg. As spreadsheets) |
| XLS or XLSX | Low      | Limits machine reading and use on non-Microsoft systems |
||| **Spatial**                |
| File Type   | Openness | Notes |
| ----------- | :------: | :---: |
| KML         | High     | An open standard developed for Google Earth. May not translate to other systems. KMZ is also available as a packaged set of KML files. |
| GeoJSON | High | A form of JSON that caters for simple geospatial attributes |
| WMS         | High     | Standardized format for georeferenced map images |
| WFS         | High     | Standardized format for geographical features |
||| **Text**                   |
| File Type   | Openness | Notes |
| ----------- | :------: | :---: |
| TXT         | High     | Simple text format readable on most operating systems. No formatting is available |
| RTF         | High     | Simple text format readable on most operating systems which retains some formatting |
| ODT         | Medium   | Limits machine reading |
| DOC or DOCX | Low      | Limits machine reading and use on non-Microsoft systems
| PDF         | Low      | Useful for document exchange to preserve formatting, but has limitations for machine reading, character recognition and remixing. |
||| ** Semi-structured** |
| File Type   | Openness | Notes |
| XML |	High |	 Extensible Markup Language (XML) is a markup language that defines a set of rules for encoding data using tags, attributes and content |
| JSON | High | JavaScript Object Notation, is an open standard format that uses human-readable text to transmit key–value pairs of data |
| RSS/ATOM | High |	An XML based standard used in data feeds/web services | 


Any **tabular** data should also be cleansed. This means that files should be:

 - Clean - Using uniform data formatting (eg; numerical dates, postcodes in every field) with no missing entries, no embedded non-text information, data in every field and as few mistakes as possible, and
 - Machine-readable – data in a  structured, predictable and non-proprietary format that can be consumed by a software program.

  

**Examples of machine readable, clean data**

| Date       | Age | Gender | Postcode |
| ---------- | --- | ------ | -------- |
| 20/10/2013 | 12  | M      | 2580     |
| 10/01/2013 | -   | F      | 1462     |
| 02/11/2011 | 22  | M      | -        |
| 12/05/2012 | 45  | F      | 1464     |
| 19/01/2010 | 75  | F      | 1800     |

**Examples of data that is not machine readable or clean**

|| Copyright of Dept. X ||
| Date       | Age     | Gender | Postcode |
| ---------- | ------- | ------ | -------- |
| 01/20/2013 | Fifteen | Female | Barton   |
| 10th Dec 11| 15      | Fem    | -        |
| 02/11/2011 | xx*     | Male   | 3652     |
| 12/05/2012 | 45      | F      | 1464     |
| * Footnote Information                |||
