Proposal
================
THE Infectious Disease Data Science Team
November 8, 2018

### Team Members

-   Thomas Carpino (tc2899)
-   George Keefer (gwk2111)
-   Matthew Perrotta (mp3653)
-   Elliot Rozen (er2867)

### Project

**Title:** Global Influenza Trends by WHO Region

**Motivation:**

All four of us are in the Infectious Disease Epidemiology Concentration and are interested in becoming aquainted with ID Epi modeling in R.

Last year, in 2018, nearly 80,000 people died from the flu in the US alone. *Check out the article [here](https://www.cnn.com/2018/09/26/health/flu-deaths-2017--2018-cdc-bn/index.html).*

Many scholars argue that there is an impending 'global threat of avian flu' due to rapid globalization and urbanization.

Understanding current patterns and trends of flu could be useful to build stronger epidemiological frameworks for disease surveillance and emergency preparedness.

Specifically, we want to examime the seasonality of inlfuenza in different regions in the world using country level influenza data.

Google flu trends

**Final products/Deliverables:**

Report, Statistical Analyses, Webpage, and Screencast

**Anticipated data sources:**

*[The WHO FluNet](http://apps.who.int/flumart/Default?ReportNo=12).*

*[The WHO General Health Observatory data repository](http://apps.who.int/gho/data/node.main.HWF10?lang=en).*

*[The World Bank Open Data](http://apps.who.int/gho/data/node.main.HWF10?lang=en).*

*[CIA World Factbook](https://www.cia.gov/library/publications/the-world-factbook/)* (For demographic data - obtained through scraping)

**Planned analyses:**

    * Logisitic Regression with outcome of epidemic threshold with interaction from various covariates
    * Linear Regression of rate vs seasonality

**Potential Indicators or Covariates:**

    * Country or Region
    * Time or Year
    * Strain
    * GDP
    * Urbanization

**Visualizations:**

    * Positive influenza cases over time, measured by year and epi week
    * Seasonal vs. pandemic influenza 
    * Seasonality of influenza by region and/or by strain

**Coding Challenges:**

A few coding challenges that we expect to face are the scale of the data, and lack of granularity. The data is countrywide, and density and urbanization are possible confounders that we may not be able to control for. There is also different sources for our data, which can pose challenges merging the datasets.

**Planned timeline:**

-   Week 1: Nov 5-8
    -   Proposal due Nov 8th
-   Week 2: Nov 12-16
    -   Project Review
    -   In Person Meeting
-   Week 3: Nov 19-23
    -   Download/scrape, consolidate, clean, tidy data
    -   Run interim models
    -   Visualizations
-   Week 4: Nov 26-30
    -   Write report
    -   Create webpage
    -   Screencast
-   Week 5: Dec 3-7
    -   December 6th:
    -   Report, Webpage, and Screencast Due (4pm)
    -   Peer Assessment Due (8pm)
    -   Final review
-   Week 6: Dec 10-14
    -   Presentations December 11
