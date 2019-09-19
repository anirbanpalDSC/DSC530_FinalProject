# Exploratory-Data-Analysis-DSC530
DSC530 Final Project for Fall 2018

<img src="Images/EDA.png" data-canonical-src="Images/EDA.png" width="200" height="200" />

# Table of contents

- [Project Background](#project-background)
- [Getting Started](#getting-started)
  - [Prerequisite](#prerequisite)
  - [Installation](#installation)
- [Usage](#usage)
- [Project Status](#project-status)
- [Versioning](#versioning)
- [Authors](#authors)
- [Acknowledgements](#acknowledgements)

## Project Background
[(Back to top)](#table-of-contents)

For the final project of DSC530, the used car database dataset has been taken from kaggle. This is one of the ideal dataset for performing EDA and taking a step towards data science. 
The dataset is taken from kaggle and contains details of the used cars in germany which are on sale on ebay.
The dataset is not clean and hence a lot of data cleaning is carried out. For e.g. prices where too high which are replaced by the median and outliers are removed accordingly. 
Also vehicles whose registration year was greater than 2016 and less than 1890 were removed from the dataset as this data is inconsistense and would yield incorrect results.
As per project instruction, the initial data analysis and cleansing part has been kept minimal and EDA part has been more elaborative.

Function to connect R to different data sources. Long term idea is to convert it in a R package. With various methods of the current solution, user should be able to connect to various data sources e.g. SQL Server and other databases, Azure SQL DB, open API etc and get data from the sources in the form of R data object, e.g. data frame.

## Getting Started
[(Back to top)](#table-of-contents)
These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on a live system.

### Prerequisite
[(Back to top)](#table-of-contents)
To execute this project, you will need the following applications 
* Python 3 
* Any R editor, e.g. R Studio, Jupyter or any other notebook

### Installation
[(Back to top)](#table-of-contents)
This particular project requires some dependent packages but the dependency would be mentioned as the part of the function and they should be installed automatically from CRAN as needed.

## Usage
[(Back to top)](#table-of-contents)
A step by step guide for etensive EDA with example of statistical interpretation and data cleansing. The code and concepts could be used as sample for other projects.

## Project Status
[(Back to top)](#table-of-contents)
Complete

## Versioning
[(Back to top)](#table-of-contents)
Git is used for project versioning.

## Authors
[(Back to top)](#table-of-contents)
Anirban Pal

## Acknowledgements
[(Back to top)](#table-of-contents)

* Image courtesy: [Datacamp](www.datacamp.com)
