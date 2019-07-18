# EPA Air Quality Analysis
# BigQuery EPA Air Quality Analysis

**Team members:**
<br>[Javier Orraca](https://javorraca.github.io/Home/)
<br>[Yiting Fu](https://github.com/Yiting2018)
<br>[Mark Planas](https://github.com/markplanas)

## Project Overview

* **Dataset**:
  * US Historical Air Quality data from the EPA (338 GB and continuously updated), accessible via BigQuery
  * Source: [Air Quality Data Collected at Outdoor Monitors Across the US](https://www.kaggle.com/epa/epa-historical-air-quality)
<br>

* **Deliverables**:
  * Interactive dashboard (via Dash or Bokeh) of a US map, showing how air quality has changed from 1950 to current date
<br>

* **Project**:
  * Analyze air quality summary statistics by year at the US county level
  * If time permits, build a neural network via TensorFlow or PyTorch, using a pipeline created in Spark / Databricks, and made available through an interactive dashboard
<br>

* **Research Questions**:
  * How US air quality changes through time at the county level;
  * What factors could cause these changes (potentially researching external data sets for understanding "why" US air quality got better or worse, etc.)

## BigQuery Data Accessibility

You can use the BigQuery Python client library to query tables in this dataset in Kernels. Note that methods available in Kernels are limited to querying data. Tables are at `bigquery-public-data.epa_historical_air_quality.[TABLENAME]`.

## Code
Please see the [Jupyter Notebook](http://htmlpreview.github.io/?https://github.com/Yiting2018/EPA-Air-Quality-Analysis/blob/master/EPA_Air_Quality_Analysis.html) for details.

## Slides
#### [Download PDF](https://github.com/Yiting2018/EPA-Air-Quality-Analysis/raw/master/Big%20Data%20Presentation.pdf)

<br>

### [Go Back to Homepage](https://yiting2018.github.io)
