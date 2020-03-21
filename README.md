# Visualizing COVID-19

<p style="font-size:80%;">(Updated by <a href="https://www.linkedin.com/in/carlos-afonso-w" target="&#95;blank" rel="noopener">Carlos Afonso</a> on March 20, 2020)</p>

Visualizing the Coronavirus Disease 2019 (COVID-19), particularly in New York City (NYC).

## New York City (NYC)

### NYC latest numbers

**March 21, 2020, 4:14 pm:** New York State Health Department's [County by County Breakdown of Positive Cases](https://coronavirus.health.ny.gov/county-county-breakdown-positive-cases){:target="&#95;blank" rel="noopener"} says that NYC has **6,211 positive cases**.

**March 20, 2020, 5:30 pm:** New York City Health Department's [COVID-19 Daily Data Summary](https://www1.nyc.gov/assets/doh/downloads/pdf/imm/covid-19-daily-data-summary.pdf){:target="&#95;blank" rel="noopener"} says that there are 5,683 total confirmed COVID-19 cases and 43 deaths in NYC.

**March 20, 2020:** [News article](https://www1.nyc.gov/office-of-the-mayor/news/173-20/mayor-de-blasio-issues-new-guidance-new-yorkers){:target="&#95;blank" rel="noopener"} from the Office of the Mayor of New York City says:

> *As of 6:00 PM today, citywide, there 5,683 positive cases of COVID-19 and 43 fatalities. Currently there are 1,514 cases in Queens 1,402 in Manhattan, 1,740 in Brooklyn,736 in the Bronx, and 285 in Staten Island.*

### NYC charts

**Note (March 21):** The charts below are from March 18. I'll replace them with a more updated version soon.

The number of COVID-19 cases in NYC (as reported by the NYC Health Dep.) started growing at a faster pace in the last few days. In particular, it more than doubled from yesterday (Mar 17) to today (Mar 18): from 814 to 1871 cases. However, this was fairly expected because 1) this is the expected behavior in the beginning (then the growth should slow down at some point and the curve will form a plateau), and 2) we were behind on the testing (hopefully there is more testing being done now and we'll get better data). Note that this data is about the number of NYC residents tested positive for COVID-19 and, in addition to the delayed testing, this data has another important limitation: the daily attribution of cases is not perfect because 1) it can take more than one day to know the result of a particular test, and 2) the data is not updated at the same time every day.

<img src="images/nyc-residents-tested-positive-for-covid-19-line.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">

While the chart above shows the total cumulative number of cases (over time), the chart below shows the number of new daily cases. As already mentioned above, the daily attribution is not perfect. So, in addition to the data points, the chart also shows the 3-day moving average to provide a more reasonable representation.

<img src="images/nyc-new-covid-19-cases.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">

The data used to create the charts above was collected from the [NYC Health Department Coronavirus webpage](https://www1.nyc.gov/site/doh/health/health-topics/coronavirus.page){:target="&#95;blank" rel="noopener"}.

The data and code used to create the charts above are available [here](https://github.com/carlos-afonso/COVID-19){:target="&#95;blank" rel="noopener"}.

### NYC data and information sources

New York City Department of Health:
* [COVID-19 webpage](https://www1.nyc.gov/site/doh/health/health-topics/coronavirus.page){:target="&#95;blank" rel="noopener"}
* [COVID-19 Daily Data Summary (.pdf)](https://www1.nyc.gov/assets/doh/downloads/pdf/imm/covid-19-daily-data-summary.pdf){:target="&#95;blank" rel="noopener"}

New York State Department of Health:
* [County by County Breakdown of Positive Cases](https://coronavirus.health.ny.gov/county-county-breakdown-positive-cases){:target="&#95;blank" rel="noopener"}
* [Press Releases](https://health.ny.gov/press/releases/2020/index.htm){:target="&#95;blank" rel="noopener"}

Office of the Mayor of New York City:
* [Latest News](https://www1.nyc.gov/office-of-the-mayor/news.page){:target="&#95;blank" rel="noopener"}

---

This webpage is part of the [COVID-19 open-source project](https://github.com/carlos-afonso/COVID-19){:target="&#95;blank" rel="noopener"}, created by [Carlos Afonso](https://www.linkedin.com/in/carlos-afonso-w){:target="&#95;blank" rel="noopener"}.
