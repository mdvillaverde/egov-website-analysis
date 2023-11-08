# egov-website-analysis

This repository contains the dataset of a website analysis using [ARIA by Equally.AI](https://equally.ai/aria), a free website auditor, of 11 e-government services from both Indonesia and the Philippines.

## 'Results.csv' contents ##
### Worksheet Columns ###
The main workbook that serves as the master data contains the following data columns within the Results worksheet. 

|**Column**|**Description**|
| -- | -- |
| Country | The two countries analyzed in this research |
| Website | The URL link of the website being analyzed |
| Category | The categorization of each website, being Government-to-Citizen (G2C), Government-to-Business (G2B) and Government-to-Government (G2G) |

The remaining columns in this worksheet are the different success criterion based on the WCAG 2.1 guidelines. They are ordered in accordance to the principles of the guidelines: Perceivable (column 4 - 32), Operable (column 33 - 61), Understandable (column 62 - 78) and Robust (column 79 - 81). More information on the WCAG 2.1 guidelines can be found on their [website](https://www.w3.org/TR/WCAG21/).

### Data Results ###
The reserach provided three different results: 0, 1, NA
|**Result**|**Description**|
| -- | -- | 
|0|The attribute was not present in the website, according to the analyzer|
|1|The attribute was present in the website, according to the analyzer|
|NA|The analyzer had failed to audit the website
