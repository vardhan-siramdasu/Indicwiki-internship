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
A government entity which is also known as government-owned enterprise or government-owned corporation or statutory corporation or government-owned-company or nationalised company in India established by the government with the objective of development, aim to control monopoly by the private sector entities, offer products and services at an affordable price to the citizens along with the role to earn profit for the government is called a Public Sector Undertaking (PSU) or a Public Sector Enterprise (PSE).

<div id='wiki'></div>

### Companies in Wikipedia
There are several Indian companies present in wikipedia and most of them are common in BSE & NSE, PSU companies. wiki companies are those which are not present in above 2 categories.

<div id='60k'></div>

### Other Indian Companies
We scraped several websites and collected 50000+ companies data based on their capital. 

## Data collection & Scraping
Most of the scraping part is done using `selenium` and `BeautifulSoup`.</br>
For the installation use the following commands in your command prompt or anaconda prompt.

``` 
pip install beautifulsoup4
pip install selenium 
```

## Translation and Transliteration
Translation and Transliteration was an important part of the project. We need to test several packages like `deep-translator`, `anuvaad` and `deeptranslit`. The translator may be works well for some kind of data, so that we need to use the best fit for our data.
For installation of above packages run the following commands in your command prompt or anaconda prompt.

```
pip install deep-translator
pip install anuvaad
pip install deeptranslit
```


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
* PSU companies xml file : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/XML%20files/ALL_PSU.xml)
* companies present in wikipedia xml file : [here](https://github.com/vardhan-siramdasu/Indicwiki-internship/blob/main/Wiki%20companies/XML%20files/company_full.xml)
* Other Indian companies xml file : [here](https://drive.google.com/file/d/1mT8U9u6kN6vNz6fUQBj3a--hTJf0QI33/view?usp=sharing)
