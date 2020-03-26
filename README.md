# Visualizing COVID-19

<p style="font-size:80%;">(Updated by <a href="https://www.linkedin.com/in/carlos-afonso-w" target="&#95;blank" rel="noopener">Carlos Afonso</a> on March 25, 2020)</p>

Visualizing the Coronavirus Disease 2019 (COVID-19), particularly in New York City (NYC).

## New York City (NYC)

### Important notes

It's important to keep the following points in mind when looking at the data/plots below about the COVID-19 situation in NYC:

* The data is collected from the "COVID-19 Daily Data Summary" updates available in the [NYC Health COVID-19 webpage](https://www1.nyc.gov/site/doh/covid/covid-19-main.page){:target="&#95;blank" rel="noopener"}.

* The data contains information about the number of cases, hospitalizations, and deaths, with breakdowns by age group, sex, and borough.

* The data in preliminary and subject to change as cases continue to be investigated.

* Note that it may take several days to get the result of a test.

* The data has one **major limitation**: The data does not include information about the number of tests performed. This information would be particularly useful to better understand the evolution of cases over time. Because, particularly in this initial stage, increasing the number of tests will very likely lead to an increase in the number of cases. So, some of the significant increases in the number of cases over time (plot below) may be partially explained by an increase in the testing capacity. For example, on March 17, a [news release from the Office of the Mayor](https://www1.nyc.gov/office-of-the-mayor/news/160-20/mayor-de-blasio-nyc-health-hospitals-bioreference-laboratories-expanded-capacity-to) announced an increase in the testing capacity in NYC, to allow 5,000 daily COVID-19 tests (starting March 19). So, some of the significant increases in the number of cases after March 19 may be partially explained by this new increased testing capacity.

* The data has one *minor limitation*: The data includes all cases treated in NYC, regardless of residence status (i.e., it includes cases in NYC residents and foreign residents treated in NYC facilities). Currently, the data does not provide a breakdown by residence status. So, we don't really know how many cases are specifically in NYC residents. However, earlier versions of the data included the residence status breakdown and the large majority of the cases were in NYC residents. So, it seems reasonable to assume that, for the current data, the large majority of the cases are NYC residents.

* Despite of the data limitations mentioned in the previous two points, it's great that NYC Health tracks and provides this important data, and with frequent updates. Moreover, this is probably one of the best (if not the best) quality COVID-19 data across all of the US. So, I appreciate and I'm grateful for NYC Health's work.

* NYC Health usually updates the data twice a day, once in the morning (11 am) and once in the evening (7 pm). This webpage is updated once a day, in the evening (with the 7 pm data update), so that the plots show the end-of-day data. Each plot explicitly states the date/time of the data being displayed.

### NYC latest numbers

Latest COVID-19 numbers in NYC, collected from the [NYC Health COVID-19 webpage](https://www1.nyc.gov/site/doh/covid/covid-19-main.page){:target="&#95;blank" rel="noopener"}

| Update Date | New<br>Cases | Total<br>Cases | Total<br>Hospitalizations | Total<br>Deaths |
| :---------------- | ---: | -----: | ------------: | ---------: |
| March 25, 5:30 pm | 4,414| 20,011 | 3,922 (19.6%) | 280 (1.4%) |
| March 24, 5:00 pm | 2,482| 15,597 | 2,883 (18.5%) | 192 (1.2%) |

Note: The plots below show the data from March 25, 2020, 5:30 pm. The plots are updated every evening (with the end-of-day data).

### NYC cases over Time

<img src="images/nyc-covid-19-total-and-new-cases-over-time.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">

### NYC cases by Age Group

<img src="images/nyc-covid-19-cases-by-age-group.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">

### NYC cases by Sex

<img src="images/nyc-covid-19-cases-by-sex.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">

### NYC cases by Borough

<img src="images/nyc-covid-19-cases-by-borough.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">

### NYC official data and information sources

New York City Department of Health:
* [COVID-19 webpage](https://www1.nyc.gov/site/doh/health/health-topics/coronavirus.page){:target="&#95;blank" rel="noopener"}
* [COVID-19 Daily Data Summary - Total Cases (.pdf)](https://www1.nyc.gov/assets/doh/downloads/pdf/imm/covid-19-daily-data-summary.pdf){:target="&#95;blank" rel="noopener"}
* [COVID-19 Daily Data Summary - Deaths (.pdf)](https://www1.nyc.gov/assets/doh/downloads/pdf/imm/covid-19-daily-data-summary-deaths.pdf){:target="&#95;blank" rel="noopener"}
* [COVID-19 Daily Data Summary - Hospitalizations (.pdf)](https://www1.nyc.gov/assets/doh/downloads/pdf/imm/covid-19-daily-data-summary-hospitalizations.pdf){:target="&#95;blank" rel="noopener"}

New York State Department of Health:
* [COVID-19 webpage](https://coronavirus.health.ny.gov){:target="&#95;blank" rel="noopener"}
* [County Breakdown of Positive COVID-19 Cases](https://coronavirus.health.ny.gov/county-county-breakdown-positive-cases){:target="&#95;blank" rel="noopener"}
* [Press Releases](https://health.ny.gov/press/releases/2020/index.htm){:target="&#95;blank" rel="noopener"}

Office of the Mayor of New York City:
* [Latest News](https://www1.nyc.gov/office-of-the-mayor/news.page){:target="&#95;blank" rel="noopener"}

The data used to create the charts above was collected from the New York City Health Department's [COVID-19 Daily Data Summary](https://www1.nyc.gov/assets/doh/downloads/pdf/imm/covid-19-daily-data-summary.pdf){:target="&#95;blank" rel="noopener"} updates.

---

This webpage is part of the [COVID-19 open-source GitHub project](https://github.com/carlos-afonso/COVID-19){:target="&#95;blank" rel="noopener"}, created by [Carlos Afonso](https://www.linkedin.com/in/carlos-afonso-w){:target="&#95;blank" rel="noopener"}.
