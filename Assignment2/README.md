# Everything Counts – Assignment 2: UK Housing Market Analysis

## Student Number  : **25000248837**

## Repository Overview

This repository contains the materials for Assignment 2 of the *Everything Counts* module.

It includes:

- A **Jupyter Notebook** (`.ipynb`) that carries out four hypothesis tests using the same dataset submitted in Assignment 1. The notebook also considers some of the normative and interpretive issues that arise when analysing this type of housing market data.  
- A **UK property price dataset** in CSV format, which is used for all analyses in the notebook.

The aim of this work is to apply statistical techniques such as hypothesis testing and regression, while also reflecting on how the structure and limitations of the dataset may affect interpretation.


## Dataset Information

### Dataset Name : UK House Price Index (HPI) -  Regional and Buyer-Type Breakdown

### Data Source

- **Primary source:** Office for National Statistics (ONS), based on data from HM Land Registry and Registers of Scotland  
- Published as part of the official **UK House Price Index (HPI)**

### Background and Context

The UK House Price Index (HPI) is an official statistic that measures changes in residential property prices across the United Kingdom. It is based on completed property transactions and provides monthly estimates of average prices and price indices at regional and local authority level.

The dataset used in this repository covers monthly observations from 2004 onwards. It includes information on:

- Average house prices  
- Price indices (including seasonally adjusted measures)  
- Monthly and annual percentage changes in prices  
- Sales volumes  

In addition, the data are broken down by several categories, including:

- **Property type** (Detached, Semi-detached, Terraced, Flats)  
- **Buyer type** (Cash buyers, Mortgage buyers, First-Time Buyers, Former Owner Occupiers)  
- **Property age** (New versus existing properties)

This level of disaggregation makes it possible to explore differences across sub-markets, rather than relying only on overall average prices.

## Data Description (Variables)

Some of the main variables used in the analysis are:

- `Date`: Month and year of observation  
- `RegionName` and `AreaCode`: Geographic identifiers  
- `AveragePrice`: Mean transaction price across all recorded sales  
- `1m%Change` and `12m%Change`: Monthly and annual percentage price changes  
- `SalesVolume`: Number of transactions recorded  
- Property-type variables (for example, `DetachedPrice`, `TerracedPrice`, `FlatPrice`)  
- Buyer-type variables (for example, `CashPrice`, `MortgagePrice`, `FTBPrice`)  
- Variables distinguishing new and existing properties, including prices and sales volumes  

The dataset is transaction-based, meaning that it only reflects properties that were sold during each period and does not include information on unsold housing or rental markets.

## Data Limitations

There are several limitations to this dataset. First, it is not fully up to date, as the most recent publication is from May 2025. In addition, the dataset is incomplete for a number of buyer-type variables, with missing values across columns relating to cash buyers, mortgage buyers, first-time buyers, and former owner occupiers (including prices, indices, percentage changes, and sales volumes). These gaps restrict the scope of longitudinal analysis and may introduce bias when comparing trends across different buyer groups.

## Use of Generative AI (Disclosure)

A free-to-use generative AI tool was used to:
- Draft a README documentation
- Refine **Python code** for data cleaning
- Search limitations in data
- Check academic sources related  

All final drafts, initial and final python code, statistical analysis, interpretation, and final written content were 


## Academic References

1. Muellbauer, J., & Murphy, A. (1997). Booms and busts in the UK housing market. *The Economic Journal*, 107(445), 1701–1727.

Additional background information is drawn from Office for National Statistics (ONS) housing market publications and reports on housing affordability in the UK.

