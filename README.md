from HTML to XML – InDesign flavour
=============================

## To do
* fix tags in footnotes, encoding problem
* check main.py that should keep only the body
* ~~inserire tabella in html~~
* ~~script note al [piede](http://www.indiscripts.com/post/2010/04/refoot-convert-markup-text-into-indesign-footnotes "Title")~~
* ~~aggiungere script per tabelle~~
* ~~rendere eseguibile lo script per le tabelle~~
* ~~inserire script per tabelle nel main [R]~~
* cercare due .doc da inserire nelle sources
* ~~aggiustare e rendere eseguibile script note (problema regex still there)~~


## Abstract
This repository includes a series of tools/scripts meant to translate HTML to XML, formatted according Adobe Indesign standards. 

Currently the process supports the following tags:

* `<h*>`
* `<p>`
* `<img>` and `<fig>`
* `<ul>`
* `<ol>`
* `<a>`
* `<q>`
* `<b>` and `<strong>`
* `<i>` and `<em>`

## Getting started

* Install [pip](https://pypi.python.org/pypi/pip): `sudo easy_install pip`
* Install lxml: `sudo pip install lxml`
* Install [Beautiful Soup](http://www.crummy.com/software/BeautifulSoup/): `sudo pip install beautifulsoup4`
* Install [InDesign](http://www.adobe.com/it/products/indesign.html)
* Copy the `ReFoot_mod.js` script into InDesign

## Step by step

* Open the terminal and go to the repository folder
* Run `python HTMLtoXML.py [yourfile.html]`
* Import `[yourfile.xml]` into InDesign: from point 4 of [this guide](http://digitalpublishingtoolkit.org/2014/05/import-html-into-indesign-via-xml/)
* Run the `ReFoot_mod.js` script

## Sources