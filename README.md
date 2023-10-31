# egov-website-analysis

This repository contains the dataset of website analysis using ARIA by Equally.AI of 11 e-government services from Indonesia and the Philippines 

## 'Results.csv' contents ##
### Worksheet Columns ###
The main workbook that serves as the master data contains the following data columns within the Results worksheet. 

|**Column**|**Description**|
| -- | -- |
|WCAG 2.1 Guidelines | A set of guidelines, established by the World Wide Web Consortium, in order to make web content more accessible to people, regardless of their disability.|
|Country | The two countries analyzed in this research|

### WCAG 2.1 Guidelines Column ###
Under this column, it is further divided into the four main principles, as established in the WCAG 2.1 guidelines
|**Column**|**Description**|
| -- | -- | 
|Perceivable|The ability to perceive the information presented|
|Operable|The ability to navigate through the user interface|
|Understandable|The ability to understand the information and how the user interface works|
|Robust|The ability to access the content as technologies and user agents evolve|

Each principle was then divided into its different guidelines, which was then further divided into differen success criterion and how they scale according to its Confornance Level. 

### Country Column ###
Under this column, the websites being analysed are categorized into three main categories: G2C, G2B and G2G
|**Column**|**Description**| **Websites Included**|
| -- | -- | -- |
|Government-to-Citizen (G2C)|The interaction between government agencies and their citizens| National Driver's Licence Servce, National Tax Service, National Immigration Service, National Health Insurance System, National Social Security System, Civil Service Commission Admission Portal, National Open data|
|Government-to-Business (G2B)|The interaction between government agencies and business owners| Online Registration of Businesses, Filing Tax for Businesses|
|Government-to-Government (G2G)|The interaction between the different government agencies, on a national, state or local level of government| Village Service Portal (ID) / Barangay Information System (PH), Government Official Assets Report Portal|

### Data Results ###
The reserach provided three different results: 0, 1, NA
|**Result**|**Description**|
| -- | -- | 
|0|The attribute was not present in the website, according to the analyzer|
|1|The attribute was present in the website, according to the analyzer|
|NA|The analyzer had failed to audit the website
