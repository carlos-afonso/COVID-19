# Visualizing COVID-19 in NYC

<p style="font-size:70%;">(Updated on April 13, 2020, by <a href="https://www.linkedin.com/in/carlos-afonso-w" target="&#95;blank" rel="noopener">Carlos Afonso</a>, a Data Scientist in NYC)</p>

Data visualizations and explanations to help understand the evolution and current status of the Coronavirus Disease 2019 (COVID-19) here in New York City (NYC).

The data presented here comes from two sources: the New York State Department of Health (Health Data NY), and the New York City Department of Health (NYC Health). The data details and limitations of the data are discussed below.

## Total counts

Total COVID-19 counts in NYC:
* reported by the City (NYC Health), as of April 12, 5 pm:
  * 178,917 total tests
  * 104,410 total cases (58% of total tests)
  * 27,676 (estimated) total hospitalizations (27% of total cases)
  * 6,182 total deaths (5.9% of total cases)
* reported by the State (Health Data NY), as of April 11:
  * 204,398 total tests
  * 103,208 total cases (50% of total tests)

<!---
  * 6,898 total deaths (as of April 12, 12:30 pm)
--->

Note: The City (NYC Health) and the State (Health Data NY) counts are different because they use different reporting methodologies.

<!---
The State is faster in including new counts in its data reports but less accurate in the date attribution. While the City is more accurate in the date attribution but slower in including new counts in its data (because it takes extra time to do a better date attribution). Because of this, for data released on the same day, the State counts are usually higher than the City counts.
--->

## Percent of positive tests over time

<img src="images/nyc-covid-19-positive-pct-over-time.svg" style="max-height:95vh; height:auto; width:auto; margin:auto; display:block;">

## New daily total and positive tests over time

<img src="images/nyc-covid-19-new-daily-tests-over-time.svg" style="max-height:95vh; height:auto; width:auto; margin:auto; display:block;">

## Cumulative total and positive tests over time

<img src="images/nyc-covid-19-cumulative-tests-over-time.svg" style="max-height:95vh; height:auto; width:auto; margin:auto; display:block;">

## New Daily Counts

<img src="images/nyc-covid-19-new-daily-counts.svg" style="max-height:95vh; height:auto; width:auto; margin:auto; display:block;">

<!---
<img src="images/nyc-covid-19-new-daily-cases-hosps-deaths.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">
--->

<!---
### NYC cases over Time

The number of total cases is expected to have an initial (potentially rapid) increase until it reaches a plateau. Nevertheless, some of the substantial increases in the number of cases may be at least partially explained by an increase in the testing capacity. For example, on March 17, a [news release from the Office of the Mayor](https://www1.nyc.gov/office-of-the-mayor/news/160-20/mayor-de-blasio-nyc-health-hospitals-bioreference-laboratories-expanded-capacity-to) announced an increase in the testing capacity in NYC, to allow 5,000 daily COVID-19 tests (starting March 19). So, some of the significant increases in the number of cases in the first days after March 19 may be partially explained by this new increased testing capacity.

<img src="images/nyc-covid-19-total-and-new-cases-over-time.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">
--->

## Rates by Age Group

<!---
The large majority (98%) of the deaths were in people with underlying conditions (Diabetes, Lung Disease, Cancer, Immunodeficiency, Heart Disease, Hypertension, Asthma, Kidney Disease, or GI/Liver Disease.)
--->

<img src="images/nyc-covid-19-rates-by-age.svg" style="max-height:95vh; height:auto; width:auto; margin:auto; display:block;">

<!---
<img src="images/nyc-covid-19-rates-by-age.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">
--->

## Rates by Sex

The charts below show NYC's COVID-19 rates by sex. More specifically the case rates, the hospitalization rates, and the death rates for each sex category (female, male, and all/everyone). Note that the rate is defined as the total count per 100,000 people. For example, the female case rate is defined as the total number of female COVID-19 cases in NYC per 100,000 females in NYC.

The charts indicate that all COVID-19 rates (case, hospitalization, and death) are higher in males than in females. Moreover, the male/female relative difference grows from the case rate to the hospitalization rate to the death rate.

<!---
Currently (Apr 6, 2020) there are 31,319 total female COVID-19 cases in NYC and it's estimated that the female population in NYC is around 4.4. million, thus the female COVID-19 rate is 713 per 100,000 people.
--->

<img src="images/nyc-covid-19-rates-by-sex.svg" style="max-height:95vh; height:auto; width:auto; margin:auto; display:block;">

<!---
### NYC cases by Borough

<img src="images/nyc-covid-19-cases-by-borough.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">
--->

## Official Data and Information Sources

New York City Department of Health (NYC Health):
* [COVID-19 homepage](https://www1.nyc.gov/site/doh/health/health-topics/coronavirus.page){:target="&#95;blank" rel="noopener"}
* [COVID-19 data homepage](https://www1.nyc.gov/site/doh/covid/covid-19-data.page){:target="&#95;blank" rel="noopener"}
* [COVID-19 data archive](https://www1.nyc.gov/site/doh/covid/covid-19-data-archive.page)
* [COVID-19 data and technical notes on Github](https://github.com/nychealth/coronavirus-data)
* [COVID-19 public health milestones](https://www1.nyc.gov/site/doh/covid/covid-19-goals.page)

Office of the Mayor of New York City:
* [Latest News](https://www1.nyc.gov/office-of-the-mayor/news.page){:target="&#95;blank" rel="noopener"}

New York State Department of Health:
* [COVID-19 homepage](https://coronavirus.health.ny.gov){:target="&#95;blank" rel="noopener"}
* [Statewide COVID-19 testing data (Health Data NY)](https://health.data.ny.gov/Health/New-York-State-Statewide-COVID-19-Testing/xdss-u53e){:target="&#95;blank" rel="noopener"}
* [COVID-19 tracker (map)](https://covid19tracker.health.ny.gov/views/NYS-COVID19-Tracker/NYSDOHCOVID-19Tracker-Map){:target="&#95;blank" rel="noopener"}
* [Press releases](https://health.ny.gov/press/releases/2020/index.htm){:target="&#95;blank" rel="noopener"}

## Important Data Notes

The data used to create the charts above is collected from the "COVID-19 Daily Data Summary" updates available on the [NYC Health COVID-19 webpage](https://www1.nyc.gov/site/doh/covid/covid-19-main.page){:target="&#95;blank" rel="noopener"}.

The data includes information about (only) the confirmed cases of people who tested positive for COVID-19 in NYC.

Due to public health guidance that people with mild illness stay home, the data may not reflect the true number of all positive COVID-19 cases in NYC.

The data is preliminary and subject to change as cases continue to be investigated. It may take several days to get the result of a test.

The data includes all cases treated in NYC, regardless of residence status. Nevertheless, it seems reasonable to assume that the large majority of the cases are NYC residents.

NYC Health usually updates the data twice a day, once in the morning (11 am) and once in the evening (7 pm). I try to update this webpage every night so that the plots show the evening (end-of-day) data. Each plot explicitly states the date/time of the data being displayed.

---

This webpage is part of the [COVID-19 open-source GitHub project](https://github.com/carlos-afonso/COVID-19){:target="&#95;blank" rel="noopener"}, created by [Carlos Afonso](https://www.linkedin.com/in/carlos-afonso-w){:target="&#95;blank" rel="noopener"}, a Data Scientist in NYC.
