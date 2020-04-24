# Scopus_crawler
> Crawl information of papers (and citing articles) searched byadvancedqueryonScopus (www.scopus.com) via Selenium.

## Table of Contents
- [Table of Contents](#table-of-contents)
- [Introduction](#introduction)
- [Installation](#installation)
- [Usage example](#usage-example)
- [Release History](#release-history)
- [Acknowledgements](#acknowledgements)

## Introduction

Crawl information (citation, bibliography, abstract, fund and other information) of papers & citing articles searched by advanced query on Scopus (www.scopus.com) via Selenium.

Specially, this program subdivides YEARS into subyear(s), then combines your QUERY and a subyear repeatedly for advanced search, given that we can only manually download at most 2000 results per batch on Scopus.

![articles_citingArticles.png](https://i.loli.net/2020/04/24/f3ckbvrABJdF1o6.png)

## Installation



## Usage example

1. Clone via GitHub Desktop or Download .zip

2. Clone from git
```sh
git clone https://github.com/matrixChimera/Scopus_crawler.git
```





## Release History

* 1.0
    * 2020/04/24
    * Create: settings.py, advanced_query_articles.py, advanced_query_citingArticles.py, and merge_ris.py

## Acknowledgements
Thanks for inspiration from @tomleung1996 (https://github.com/tomleung1996/wos_crawler)

