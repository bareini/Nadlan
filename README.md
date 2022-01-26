# Nadlan

Housing prices in Israel have nearly doubled is the passed decade [1]. After halting (and even slightly decreasing) during the first waves of Covid-19, they are keep rising. 
The best we can do is to be informed and learn the market ourselves to avoide "bad deals".

**These notebooks mine and analyze recent real estate transactions**. 

*NADLAN.GOV* website aims to provide public access to information regrading real-estate transactions documented in goverment databases [2]. 
This rather user-friendly allows quering according to specific neighborhoods and streets. But, in order to gain a broader understanding of the markets behavior, relevant information is scraped for macro analysis.
*Note* that important features for determining house value are missing from this website. We must analyze with caution. *Nadlan2* decribes these aspectes at length.

- *Nadlan1* is designated for a quick&dirty scraping. You ca easelly modify to include your own queries.
- *Nadlan2* is the analysis notebook which provides different insignts to important aspects of house value. It is a guide for inform analysis from the macro -> micro.


## Important Notes
(a) This directory does not include data - in compliance with the site's terms of use.

(b) The true value of a property is determined by an appraiser. The estimates suggested are just to get started, it is recommanded to consult professionals.


## Dependencies
*Nadlan1* relies on ``selenuim`` tool from scraping and requires download ``chromdriver``. 
In details:
- ``selenuim``
- ``chromdriver``
- ``seaborn``
- ``pprint``
- ``pandas``
- -``numpy``
- ``matplotlib``

## References
<a id="1">[1]</a> 
https://www.timesofisrael.com/israeli-housing-prices-have-nearly-doubled-in-a-decade-with-no-signs-of-slowing

<a id="2">[2]</a> 
https://www.nadlan.gov.il/about
