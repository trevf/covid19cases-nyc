# COVID-19 Cases in New York City

This repository contains the source code for **[covid19cases.nyc](//covid19cases.nyc)**, which is a visualization of New York City's confirmed coronavirus disease (COVID-19) cases and deaths to date.

It also contains an **archive of all daily NYC COVID-19 case summary PDFs** that have been provided by the New York City Department of Health and Mental Hygiene (NYC DOHMH) since March 18, 2020, and a compiled **CSV of all NYC COVID-19 confirmed case and death counts** since February 29, 2020.

## About the data

Since the beginning of the coronavirus disease outbreak in New York City, the NYC DOHMH has regularly published confirmed case counts on their [Coronavirus Disease 2019 (COVID-19) website](https://www1.nyc.gov/site/doh/covid/covid-19-main.page). Until March 18, 2020, these case counts were published inline; on March 19, 2020, the NYC DOHMH began uploading daily case summaries in PDF format (starting with data as of March 18).

In some instances, the NYC DOHMH has published multiple updates in a single day. The visualization on [covid19cases.nyc](//covid19cases.nyc) always references the largest count reported in any given day, except where data reported on the NYC DOHMH COVID-19 website conflicts with data presented in a later case summary PDF (in which event the data from the later case summary PDF is used instead). Because the NYC DOHMH has not provided COVID-19–related death counts prior to March 18, 2020, this data set has also been supplemented by information gathered from various public news reports.

Because updates to the NYC DOHMH COVID-19 website have been somewhat sporadic, the visualization and archive are currently updated **manually** based on data collected by a web-scraping tool.