# TSIR
## [Confirmed](https://github.com/HuangDerek/TSIR/tree/main/Confirmed)

This folder contains the number of reported confirmed cases for 58 US states and territories from 1/22/2020 to 2/14/2021 respectively.

### File Naming Convention
State_confirmed.csv

### Field Description
* <b>Day</b>: Numerical numbering of the data with 1/22/2020 as day 1
* <b>Date</b>: The date of the corresponding reported confirmed cases data in the form M/D/Y
* <b>Total</b>: The total number of confirmed cases on the corresponding days and dates

### Data sources
[JHU CSSE COVID-19 Dataset](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data#daily-reports-csse_covid_19_daily_reports)

## [Deaths](https://github.com/HuangDerek/TSIR/tree/main/Deaths)

This folder contains the number of reported deaths for 58 US states and territories from 1/22/2020 to 2/14/2021 respectively.

### File Naming Convention
State_deaths.csv

### Field Description
* <b>Day</b>: Numerical numbering of the data with 1/22/2020 as day 1
* <b>Date</b>: The date of the corresponding death data in the form M/D/Y
* <b>Total</b>: The total number of deaths on the corresponding days and dates

### Data sources
[JHU CSSE COVID-19 Dataset](https://github.com/CSSEGISandData/COVID-19/tree/master/csse_covid_19_data#daily-reports-csse_covid_19_daily_reports)

## [Mobility](https://github.com/HuangDerek/TSIR/tree/main/Mobility)

This folder contains mobility reports for the 50 US states and  from 1/22/2020 to 2/14/2021 respectively.

### File Naming Convention
State_Mobility.csv

### Key Field Description
* <b>country_region_code</b>: Alpha-2 country code (US in this case)
* <b>country_region</b>: Full country name (United States in this case)
* <b>sub_region_1</b>: The state (or district) of the corresponding data
* <b>iso_3166_2_code</b>: The ISO 3166-2 code for the corresponding state
* <b>date</b>: The date of the corresponding data in the form M/D/Y
* <b>_percent_change_from_baseline</b>: Percentage change in mobility from baseline for corresponding areas

Specific data information [here](https://www.google.com/covid19/mobility/data_documentation.html?hl=en)

### Data sources
[Google COVID-19 Community Mobility Reports](https://www.google.com/covid19/mobility/)
