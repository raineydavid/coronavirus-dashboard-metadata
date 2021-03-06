﻿> 20 October 2020: Read the Public Health Matters blog [The COVID-19 dashboard: a design and feature evolution](https://publichealthmatters.blog.gov.uk/2020/10/20/covid-19-dashboard-a-design-and-feature-evolution/)

## Table of contents

## Introduction

The dashboard presents progress of the coronavirus pandemic as an up to date and authoritative summary of key information. This includes levels of infections, the impact on health in the UK and on measures taken to respond.  It presents a dynamic contemporary picture and is updated daily. 

It meets a strongly expressed need from the public for timely updates at national and local level to ensure good understanding of the day to day progress of the pandemic. This is achieved through interactive maps and trends over time of key measures relating to testing capacity and activity, newly confirmed cases, hospital admissions and deaths.

The dashboard provides a tool for developers and analysts by supporting reuse of data through access to the results in machine readable files and via an API.
To ensure high public value and quality, the statistics are presented in line with the Code of Practice for Statistics. Information is provided on the strengths and weaknesses of the data to help users to interpret them correctly. 

Full definitions for the metrics presented in the dashboard are provided below.

## R number and growth rate

Estimated COVID-19 R number and growth rate on the reporting date, expressed as ranges.

{inc:base/rNumberRate.md|modals}

## Daily and cumulative numbers of tests

Number of lab-confirmed positive, negative or void COVID-19 test results, across all types of testing, reported on or up to the reporting date.

{inc:base/tests_processed.md|modals}

## Testing capacity

Total number of tests capable of being performed by laboratories on the reporting date.

{inc:base/testingCapacity.md|modals}

## Daily and cumulative numbers of cases 

Number of people with a lab-confirmed positive COVID-19 virus test on or up to the specimen date or reporting date (depending on availability).

{inc:base/cases.md|modals}

## Daily and cumulative numbers of patients admitted to hospital

Numbers of patients admitted to hospital with COVID-19 on or up to the reporting date. 

{inc:base/admissions.md|modals}

## Patients in hospital

Total number of confirmed COVID-19 patients in hospital on the reporting date.

{inc:base/patientsInHospital.md|modals}

## Patients in mechanical ventilation beds

Total number of mechanical ventilation beds that are occupied by COVID-19 patients on the reporting date.

{inc:base/covidPatientsInMVBeds.md|modals}

## Daily and cumulative deaths within 28 days of a positive test

Total number of people who had a positive test result for COVID-19 and died within 28 days of the first
positive test, reported on or up to the date of death or reporting date (depending on availability).

{inc:base/deaths28Days.md|modals}

## Methodologies

{inc:base/sevenDayMetrics.md|modals}

{inc:base/rates.md|modals}

{inc:base/rolling_averages.md|modals}

## Downloads

{inc:base/msoaCases.md|modals}

We are no longer publishing data at LSOA level on advice from the Statistical Disclosure Control unit at the Office for National Statistics. 

### Legacy CSV downloads

The CSV downloads provided from the previous version of the dashboard are available on the links below.

* [Cases](https://coronavirus.data.gov.uk/downloads/csv/coronavirus-cases_latest.csv)

* The legacy deaths download is no longer available as the data series has been discontinued.

These files will be updated alongside the main website on a daily basis for the foreseeable future.
However, users are strongly recommended to use the API instead, which give access to the full range of
data in the live site. See the [Developer's guide](https://coronavirus-staging.data.gov.uk/developers-guide)
for details.