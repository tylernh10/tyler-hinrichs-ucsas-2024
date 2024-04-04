# tyler-hinrichs-ucsas-2024

Materials for my workshop at [UCSAS 2024](https://statds.org/events/ucsas2024/index.html)!

This repository includes some rmarkdown slides used to talk about webscraping, then some .ipynb notebooks to show how we can scrape data from the [English Premier League's website](https://www.premierleague.com/).

**IMPORTANT:** Everything you need for [static_soccer_data.ipynb](https://github.com/tylernh10/tyler-hinrichs-ucsas-2024/blob/main/static_soccer_data.ipynb) is already there in the notebook. For [dynamic_soccer_data.ipynb](https://github.com/tylernh10/tyler-hinrichs-ucsas-2024/blob/main/dynamic_soccer_data.ipynb), you will use Selenium, which has some additional setup required. Please refer to the [section below](#dynamic-data).

## Web Scraping for Sports Data

If you want to start analyzing sports, you need data. Nowadays, there are many sources of pre-built datasets, but at times, you might want to make a custom dataset from an online source. Web scraping is the most effective solution to this problem. You can automate the process of gathering data from webpages, and in doing so, you can create datasets specific to the questions that you want to be answered. During this workshop you will learn 1) what web scraping is, 2) how static web scraping works using Python packages pandas, requests, and BeautifulSoup, then 3) how dynamic web scraping works using Python package Selenium in conjunction with the previously learned packages.

#### Static Data
- static_soccer_data.ipynb
- We use 3 Python libraries, Requests, BeautifulSoup4, and Pandas, which can be installed with commands in the notebook

#### Dynamic Data
- dynamic_soccer_data.ipynb
- **In the notebook, I use Chrome.**
- We use 3 Python libraries, Selenium, BeautifulSoup4, and Pandas, which can be installed with commands in the notebook
- We must use a ChromeDriver for full functionality
- The version **must match your downloaded Chrome instance**:
  - In Chrome, visit [chrome://settings/help](chrome://settings/help) and check the number before the first period in the version number. Example: **123**.X.XXXX.XXX
  - Chrome version <=114: https://chromedriver.chromium.org/downloads
  - Chrome version >114: https://googlechromelabs.github.io/chrome-for-testing/

### Slides
- Have been created using rmarkdown
- Access through the .rmd file (need R to run) or through the html file

### Other Information:

