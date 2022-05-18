# Indicwiki-internship
Creating intelligent programs for generating Telugu and Hindi content using Artificial Intelligence, Machine Learning, Natural Language toolkits and openly available structured data sources in a specific domain like Programming languages, Software companies, cities, scientists, BSE companies, hospitals, universities/colleges, Movies, Actors, etc.


![](https://img.shields.io/badge/python-%20v3.7.3-blue)
![](https://img.shields.io/badge/selenium-v4.1.5%20web%20scraping-lightgrey)
![](https://img.shields.io/badge/deep--translator-v1.8.3%20en%20--%3E%20te-blue)
![](https://img.shields.io/badge/Jinja-templating-red)

#### Requirements : 
We need specific package versions for the setup of our virtual environment for the project.</br>
Link for the requirements : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/requirements.txt)

## Domain : INDIAN COMPANIES
There more than 2 Million+ companies exist in India. Our aim is to generate articles for 50000+ companies in Telugu so that we divided the companies into 4 categories based on their nature and organization. 

* [*BSE & NSE Companies*](#bsense)
* [*Public Sector Undertakings (PSU)*](#psu)
* [*Companies in Wikipedia*](#wiki)
* [*Other Indian Companies*](#60k)

<div id='bsense'></div>

### BSE & NSE Companies
The BSE SENSEX (also known as the S&P Bombay Stock Exchange Sensitive Index or simply SENSEX) is a free-float market-weighted stock market index of 30 well-established and financially sound companies listed on the Bombay Stock Exchange.

<div id='psu'></div>

### Public Sector Undertakings (PSU)
A government entity which is also known as government-owned enterprise or government-owned corporation or statutory corporation or government-owned-company or nationalised company in India established by the government with the objective of development, aim to control monopoly by the private sector entities, offer products and services at an affordable price to the citizens along with the role to earn profit for the government is called a Public Sector Undertaking (PSU) or a Public Sector Enterprise (PSE). These establishments are wholly or partly owned by the Government of India and/or one of the many state or territorial governments. Central Public Sector Undertakings (CPSU, CPSE) are wholly or partly owned by the Government of India, while State Public Sector Undertakings (SPSU, SPSE) are wholly or partly owned by state or territorial governments.

<div id='wiki'></div>

### Companies in Wikipedia
companies present in wikipedia.

<div id='60k'></div>

### Other Indian Companies
We collected more than 57000+ companies data. 

## Scraping
scraping is done using selenium and BeautifulSoup.

## Translation

## Jinja Templating
We use Jinja templating tool for the creating articles in Telugu. We use randomized the sentence formation to maku sure that each article has different kind of sentenses.</br>
Jinja templates for all four categories of companies :
* BSE & NSE companies : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/indian%20companies%20bse%20nse/templates/company.j2)
* PSU companies : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/templates/PSU_companies.j2)
* wiki companies : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/Wiki%20companies/Templates/introduction.j2)
* other companies : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/templates/remaining%20Indian%20companies.j2)



## Article(XML) Generation
We generated 4 different XML files for each of the category.</br>
> The code for the generating the XML file is provided here : [XML generator](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/XMLgen.ipynb)
* BSE & NSE companies xml file : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/indian%20companies%20bse%20nse/xml%20files/final_wiki_company.xml)
* PSU companies xml file : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/XML%20files/PSU_all.xml)
* companies present in wikipedia xml file : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/Wiki%20companies/XML%20files/company_full.xml)
* Other Indian companies xml file : [here]()
