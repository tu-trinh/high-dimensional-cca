# Data For Project

Below are each of the datasets used in the Andreou paper. They appear (roughly) in row order for their respective tables.

Important note: the below files were too big to be stored as a single dataframe, so they were split up into chunks. For example, `dev_100_1991_1.csv`, `dev_100_1991_2.csv`, etc. Make sure to concatenate all the chunks when using the data.
- dev_100_1991
- dev_exUS_100_1991
- euro_100_1991
- jap_100_1991
- na_100_2008
- na_100_1991


## Table 3 Datasets
| Official Dataset Name(s) | Name in Files | Abbreviation in Paper | Large or Small Panel | Years | Source |
| ------------------------ | ------------- | --------------------- | -------------------- | ----- | ------ |
| 100 Portfolios Formed on Size and Book-to-Market (10 x 10) | us_100_2008 | 100 US Port. | Large | 2008 - 2019 | Kenneth French |
| 100 Portfolios Formed on Size and Book-to-Market (10 x 10) | us_100_1964 | 100 US Port. | Large | 1964 - 2019 | Kenneth French |
| Fama/French 3 Factors | us_ff3_2008 | US 3 FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French 3 Factors | us_ff3_1964 | US 3 FF | Small | 1964 - 2019 | Kenneth French |
| Fama/French 5 Factors | us_ff5_2008 | US 5 FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French 5 Factors | us_ff5_1964 | US 5 FF | Small | 1964 - 2019 | Kenneth French |
| Fama/French 5 Factors, Momentum Factor (Mom) | us_ff5_mom_2008 | US 5 FF + MOM | Small | 2008 - 2019 | Kenneth French |
| Fama/French 5 Factors, Momentum Factor (Mom) | us_ff5_mom_1964 | US 5 FF + MOM | Small | 1964 - 2019 | Kenneth French |
| 5 Industry Portfolios | us_5_2008 | 5 US Industry Port. | Small | 2008 - 2019 | Kenneth French |
| 5 Industry Portfolios | us_5_1964 | 5 US Industry Port. | Small | 1964 - 2019 | Kenneth French |
| 10 Industry Portfolios | us_10_2008 | 10 US Industry Port. | Small | 2008 - 2019 | Kenneth French |
| 10 Industry Portfolios | us_10_1964 | 10 US Industry Port. | Small | 1964 - 2019 | Kenneth French |
| N/A | N/A | 7 US companies | Small | 2013 - 2019 | NASDAQ |
| N/A | N/A | 5 US companies | Small | 2008 - 2019 | NASDAQ |


## Table 4 Datasets
| Official Dataset Name(s) | Name in Files | Abbreviation in Paper | Large or Small Panel | Years | Source |
| ------------------------ | ------------- | --------------------- | -------------------- | ----- | ------ |
| 25 Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Portfolios Formed on Size and Operating Profitability, 25 Portfolios Formed on Size and Investment (5 x 5), 25 Portfolios Formed on Size and Momentum (5 x 5) | na_100_2008 | 4x25 North American Port. | Large | 2008 - 2019 | Kenneth French |
| 25 Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Portfolios Formed on Size and Operating Profitability, 25 Portfolios Formed on Size and Investment (5 x 5), 25 Portfolios Formed on Size and Momentum (5 x 5) | na_100_1991 | 4x25 North American Port. | Large | 1991 - 2019 | Kenneth French |
| Fama/French North American 5 Factors | na_ff5_2008 | 5 North American FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French North American 5 Factors | na_ff5_1991 | 5 North American FF | Small | 1991 - 2019 | Kenneth French |
| Fama/French North American 5 Factors, North American Momentum Factor (Mom) | na_ff5_mom_2008 | 5 North American FF + MOM | Small | 2008 - 2019 | Kenneth French |
| Fama/French North American 5 Factors, North American Momentum Factor (Mom) | na_ff5_mom_1991 | 5 North American FF + MOM | Small | 1991 - 2019 | Kenneth French |
| 5 Industry Portfolios | us_5_2008 | 5 US Industry Port. | Small | 2008 - 2019 | Kenneth French |
| 5 Industry Portfolios | us_5_1991 | 5 US Industry Port. | Small | 1991 - 2019 | Kenneth French |
| 10 Industry Portfolios | us_10_2008 | 10 US Industry Port. | Small | 2008 - 2019 | Kenneth French |
| 10 Industry Portfolios | us_10_1991 | 10 US Industry Port. | Small | 1991 - 2019 | Kenneth French |
| N/A | N/A | 7 US companies | Small | 2013 - 2019 | NASDAQ |
| N/A | N/A | 5 US companies | Small | 2008 - 2019 | NASDAQ |


## Table 5 Datasets
| Official Dataset Name(s) | Name in Files | Abbreviation in Paper | Large or Small Panel | Years | Source |
| ------------------------ | ------------- | --------------------- | -------------------- | ----- | ------ |
| 25 Developed Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Developed Portfolios Formed on Size and Operating Profitability (5 x 5), 25 Developed Portfolios Formed on Size and Investment (5 x 5), 25 Developed Portfolios Formed on Size and Momentum (5 x 5) | dev_100_2008 | 4x25 Developed incl. US Port. | Large | 2008 - 2019 | Kenneth French |
| 25 Developed Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Developed Portfolios Formed on Size and Operating Profitability (5 x 5), 25 Developed Portfolios Formed on Size and Investment (5 x 5), 25 Developed Portfolios Formed on Size and Momentum (5 x 5) | dev_100_1991 | 4x25 Developed incl. US Port. | Large | 1991 - 2019 | Kenneth French |
| Fama/French Developed 5 Factors | dev_ff5_2008 | 5 Developed FF incl. US | Small | 2008 - 2019 | Kenneth French |
| Fama/French Developed 5 Factors | dev_ff5_1991 | 5 Developed FF incl. US | Small | 1991 - 2019 | Kenneth French |
| 25 Developed ex US Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Developed ex US Portfolios Formed on Size and Operating Profitability (5 x 5), 25 Developed ex US Portfolios Formed on Size and Investment (5 x 5), 25 Developed ex US Portfolios Formed on Size and Momentum (5 x 5) | dev_exUS_100_2008 | 4x25 Developed ex. US Port. | Large | 2008 - 2019 | Kenneth French |
| 25 Developed ex US Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Developed ex US Portfolios Formed on Size and Operating Profitability (5 x 5), 25 Developed ex US Portfolios Formed on Size and Investment (5 x 5), 25 Developed ex US Portfolios Formed on Size and Momentum (5 x 5) | dev_exUS_100_1991 | 4x25 Developed ex. US Port. | Large | 1991 - 2019 | Kenneth French |
| Fama/French Developed ex US 5 Factors | dev_exUS_ff5_2008 | 5 Developed FF ex. US | Small | 2008 - 2019 | Kenneth French |
| Fama/French Developed ex US 5 Factors | dev_exUS_ff5_1991 | 5 Developed FF ex. US | Small | 1991 - 2019 | Kenneth French |
| 25 European Portfolios Formed on Size and Book-to-Market (5 x 5), 25 European Portfolios Formed on Size and Operating Profitability (5 x 5), 25 European Portfolios Formed on Size and Investment (5 x 5), 25 European Portfolios Formed on Size and Momentum (5 x 5) | euro_100_2008 | 4x25 Euoprean Port. | Large | 2008 - 2019 | Kenneth French |
| 25 European Portfolios Formed on Size and Book-to-Market (5 x 5), 25 European Portfolios Formed on Size and Operating Profitability (5 x 5), 25 European Portfolios Formed on Size and Investment (5 x 5), 25 European Portfolios Formed on Size and Momentum (5 x 5) | euro_100_1991 | 4x25 Euoprean Port. | Large | 1991 - 2019 | Kenneth French |
| Fama/French European 5 Factors | euro_ff5_2008 | 5 European FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French European 5 Factors | euro_ff5_1991 | 5 European FF | Small | 1991 - 2019 | Kenneth French |
| 25 Japanese Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Japanese Portfolios Formed on Size and Operating Profitability (5 x 5), 25 Japanese Portfolios Formed on Size and Investment (5 x 5), 25 Japanese Portfolios Formed on Size and Momentum (5 x 5) | jap_100_2008 | 4x25 Japanese Port. | Large | 2008 - 2019 | Kenneth French |
| 25 Japanese Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Japanese Portfolios Formed on Size and Operating Profitability (5 x 5), 25 Japanese Portfolios Formed on Size and Investment (5 x 5), 25 Japanese Portfolios Formed on Size and Momentum (5 x 5) | jap_100_1991 | 4x25 Japanese Port. | Large | 1991 - 2019 | Kenneth French |
| Fama/French Japanese 5 Factors | jap_ff5_2008 | 5 Japanese FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French Japanese 5 Factors | jap_ff5_1991 | 5 Japanese FF | Small | 1991 - 2019 | Kenneth French |
| 25 Asia Pacific ex Japan Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Asia Pacific ex Japan Portfolios Formed on Size and Operating Profitability (5 x 5), 25 Asia Pacific ex Japan Portfolios Formed on Size and Investment (5 x 5), 25 Asia Pacific ex Japan Portfolios Formed on Size and Momentum (5 x 5) | asia_100_2008 | 4x25 Asia Pacific ex Japan Port. | Large | 2008 - 2019 | Kenneth French |
| 25 Asia Pacific ex Japan Portfolios Formed on Size and Book-to-Market (5 x 5), 25 Asia Pacific ex Japan Portfolios Formed on Size and Operating Profitability (5 x 5), 25 Asia Pacific ex Japan Portfolios Formed on Size and Investment (5 x 5), 25 Asia Pacific ex Japan Portfolios Formed on Size and Momentum (5 x 5) | asia_100_1991 | 4x25 Asia Pacific ex Japan Port. | Large | 1991 - 2019 | Kenneth French |
| Fama/French Asia Pacific ex Japan 5 Factors | asia_ff5_2008 | 5 Asia Pacific ex Japan FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French Asia Pacific ex Japan 5 Factors | asia_ff5_1991 | 5 Asia Pacific ex Japan FF | Small | 1991 - 2019 | Kenneth French |
| Fama/French Developed 5 Factors, Developed Momentum Factor (Mom) | dev_ff5_mom_2008 | 5 Developed FF incl. US + MOM | Small | 2008 - 2019 | Kenneth French |
| Fama/French Developed 5 Factors, Developed Momentum Factor (Mom) | dev_ff5_mom_1991 | 5 Developed FF incl. US + MOM | Small | 1991 - 2019 | Kenneth French |
| Fama/French Developed ex US 5 Factors, Developed ex US Momentum Factor (Mom) | dev_exUS_ff5_mom_2008 | 5 Developed FF ex. US + MOM | Small | 2008 - 2019 | Kenneth French |
| Fama/French Developed ex US 5 Factors, Developed ex US Momentum Factor (Mom) | dev_exUS_ff5_mom_1991 | 5 Developed FF ex. US + MOM | Small | 1991 - 2019 | Kenneth French |
| Fama/French European US 5 Factors, European Momentum Factor (Mom) | euro_ff5_mom_2008 | 5 European FF + MOM | Small | 2008 - 2019 | Kenneth French |
| Fama/French European 5 Factors, European Momentum Factor (Mom) | euro_ff5_mom_1991 | 5 European FF + MOM | Small | 1991 - 2019 | Kenneth French |
| Fama/French Japanese 5 Factors, Japanese Momentum Factor (Mom) | jap_ff5_mom_2008 | 5 Japanese FF + MOM | Small | 2008 - 2019 | Kenneth French |
| Fama/French Japanese 5 Factors, Japanese Momentum Factor (Mom) | jap_ff5_mom_1991 | 5 Japanese FF + MOM | Small | 1991 - 2019 | Kenneth French |
| Fama/French Asia Pacific ex Japan 5 Factors, Asia Pacific ex Japan Momentum Factor (Mom) | asia_ff5_mom_2008 | 5 Asia Pacific ex Japan FF + MOM | Small | 2008 - 2019 | Kenneth French |
| Fama/French Asia Pacific ex Japan 5 Factors, Asia Pacific ex Japan Momentum Factor (Mom) | asia_ff5_mom_1991 | 5 Asia Pacific ex Japan FF + MOM | Small | 1991 - 2019 | Kenneth French |


## Table 6 Datasets
| Official Dataset Name(s) | Name in Files | Abbreviation in Paper | Large or Small Panel | Years | Source |
| ------------------------ | ------------- | --------------------- | -------------------- | ----- | ------ |
| Country Portfolios formed on B/M, E/P, CE/P, and D/P | country_2008 | 210 Country Port. | Large | 2008 - 2019 | Kenneth French |
| Country Portfolios formed on B/M, E/P, CE/P, and D/P | country_1991 | 210 Country Port. | Large | 1991 - 2019 | Kenneth French |
| Fama/French Developed 5 Factors | dev_ff5_2008 | 5 Developed FF incl. US | Small | 2008 - 2019 | Kenneth French |
| Fama/French Developed 5 Factors | dev_ff5_1991 | 5 Developed FF incl. US | Small | 1991 - 2019 | Kenneth French |
| Fama/French Developed ex US 5 Factors | dev_exUS_ff5_2008 | 5 Developed FF ex. US | Small | 2008 - 2019 | Kenneth French |
| Fama/French Developed ex US 5 Factors | dev_exUS_ff5_1991 | 5 Developed FF ex. US | Small | 1991 - 2019 | Kenneth French |
| Fama/French 5 Factors | us_ff5_2008 | US 5 FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French 5 Factors | us_ff5_1991 | US 5 FF | Small | 1991 - 2019 | Kenneth French |
| Fama/French European 5 Factors | euro_ff5_2008 | 5 European FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French European 5 Factors | euro_ff5_1991 | 5 European FF | Small | 1991 - 2019 | Kenneth French |
| Fama/French Japanese 5 Factors | jap_ff5_2008 | 5 Japanese FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French Japanese 5 Factors | jap_ff5_1991 | 5 Japanese FF | Small | 1991 - 2019 | Kenneth French |
| Fama/French Asia Pacific ex Japan 5 Factors | asia_ff5_2008 | 5 Asia Pacific ex Japan FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French Asia Pacific ex Japan 5 Factors | asia_ff5_1991 | 5 Asia Pacific ex Japan FF | Small | 1991 - 2019 | Kenneth French |
| Fama/French North American 5 Factors | na_ff5_2008 | 5 North American FF | Small | 2008 - 2019 | Kenneth French |
| Fama/French North American 5 Factors | na_ff5_1991 | 5 North American FF | Small | 1991 - 2019 | Kenneth French |
