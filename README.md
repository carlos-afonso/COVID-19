# Visualizing COVID-19

<p style="font-size:75%;">(Updated by <a href="https://www.linkedin.com/in/carlos-afonso-w" target="&#95;blank" rel="noopener">Carlos Afonso</a> on March 19, 2020)</p>

Visualizing the Coronavirus Disease 2019 (COVID-19).

## New York City (NYC)

**Update (March 19):** The NYC Health Dep. just started sharing more detailed data, but now counting all cases treated in NYC (not only residents as before and as used in the visualizations below). This new and more detailed data is now being shared in this [PDF file](https://www1.nyc.gov/assets/doh/downloads/pdf/imm/covid-19-daily-data-summary.pdf). I'll collect and visualize this data soon.

The number of COVID-19 cases in NYC (as reported by the NYC Health Dep.) started growing at a faster pace in the last few days. In particular, it more than doubled from yesterday (Mar 17) to today (Mar 18): from 814 to 1871 cases. However, this was fairly expected because 1) this is the expected behavior in the beginning (then the growth should slow down at some point and the curve will form a plateau), and 2) we were behind on the testing (hopefully there is more testing being done now and we'll get better data). Note that this data is about the number of NYC residents tested positive for COVID-19 and, in addition to the delayed testing, this data has another important limitation: the daily attribution of cases is not perfect because 1) it can take more than one day to know the result of a particular test, and 2) the data is not updated at the same time every day. However, this is the only official data currently being provided by the NYC Health Dep. and I'm trying to make the best of it to track and understand the evolution of COVID-19 here in NYC.

<img src="images/nyc-residents-tested-positive-for-covid-19-line.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">

While the chart above shows the total cumulative number of cases (over time), the chart below shows the number of new daily cases. As already mentioned above, the daily attribution is not perfect. So, in addition to the data points, the chart also shows the 3-day moving average to provide a more reasonable representation.

<img src="images/nyc-new-covid-19-cases.svg" style="max-width:500px; width:98%; height:auto; margin:auto; display:block;">

The data used to create the charts above was collected from the [NYC Health Department Coronavirus webpage](https://www1.nyc.gov/site/doh/health/health-topics/coronavirus.page){:target="&#95;blank" rel="noopener"}.

The data and code used to create the charts above are available [here](https://github.com/carlos-afonso/COVID-19){:target="&#95;blank" rel="noopener"}.

This webpage is part of the [COVID-19 open-source project](https://github.com/carlos-afonso/COVID-19){:target="&#95;blank" rel="noopener"}, created by [Carlos Afonso](https://www.linkedin.com/in/carlos-afonso-w){:target="&#95;blank" rel="noopener"}.
