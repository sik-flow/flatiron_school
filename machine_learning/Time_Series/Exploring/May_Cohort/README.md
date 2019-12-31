---
title: 
layout: post
weight: 10
hidden: true
---

===


**Course**: DS   <br/>
**Mod**: Mod 4 Sec 31 V2         <br/>
**Topic**: Time Series: Stationarity, Differencing and Autocorrelation  <br/>
**Amount of time**: 60 minutes <br/>
**Author**: Vishal Patel 


***

#### Lesson Summary:

This lesson starts by defining time series and discussing stationarity. This leads into a brief sorting activity and discussion regarding whether various time series graphs are stationary.  From there, the Dickey Fuller test is introduced in order to determine the stationarity of a time series dataset. From there, differencing is introduced using a dataset which is imported via Pandas. Afterwards, autocorrelation is discussed and both ACF and PACF plots are explored. Two additional datasets which may be useful as starting points for additional opportunities for student practice and exploration are also outlined in the `Additional Time Series Explorations.ipynb` file.

#### Topic:

Time Series

#### Learning goals for this lesson:

* Determine from a graph if a time series has a constant or changing variance.
* Determine from a graph if a time series has a constant or changing mean.
* Determine from a graph if a time series dataset is stationary.
* Make a nonstationary time series stationary using differencing.
* Plot the autocorrelation function for a given time series.
* Plot the partial autocorrelation function (pacf) for a given time series.

Extension:

* Perform the Dickey Fuller test to assess stationarity using scipy.

#### Prerequisite knowledge:

* Students should have a working knowledge of Pandas.
* Students should understand the concept of variance.
* Students should understand the concept of covariance.

#### Prequisite Learn-Materials:

* [Introduction to Time Series](https://github.com/learn-co-curriculum/dsc-introduction-to-time-series)
* [Types of Trends](https://github.com/learn-co-curriculum/dsc-types-of-trends)
* [Removing Trends](https://github.com/learn-co-curriculum/dsc-removing-trends)

#### Post Learn-Materials:

* [Managing Time Series Data - Lab](https://github.com/learn-co-curriculum/dsc-managing-time-series-data-lab)
* [Visualizing Time Series Data - Lab](https://github.com/learn-co-curriculum/dsc-visualizing-time-series-data-lab)
* [Testing for Trends - Lab](https://github.com/learn-co-curriculum/dsc-testing-for-trends-lab)
* [Removing Trends - Lab](https://github.com/learn-co-curriculum/dsc-removing-trends-lab)
* [Time Series Decomposition](https://github.com/learn-co-curriculum/dsc-time-series-decomposition)

#### Relevant learning goals from Airtable: 

BASIC_TIME_SERIES.1.rec03PIA5vj1IMSRy
BASIC_TIME_SERIES.1.recarO13YCrvJOEmT
BASIC_TIME_SERIES.1.rec6kYchX5QLTY9dR
BASIC_TIME_SERIES.1.recUDexHRUwvjC3EU
BASIC_TIME_SERIES.1.recg9UYpleKVwCSt6 

BASIC_TIME_SERIES.2.recCGEPhyg8tf6DmM
BASIC_TIME_SERIES.2.recyDPpWOznGlEHmA
BASIC_TIME_SERIES.2.recqsLmiabpxX7yLJ
BASIC_TIME_SERIES.2.recU1CKGXZeFVJJWz
BASIC_TIME_SERIES.2.recAqWztP4wjUEhIw
BASIC_TIME_SERIES.2.recJ7pxumTQ6VXJfx
BASIC_TIME_SERIES.2.rechpAouw1Z9f4Scn
BASIC_TIME_SERIES.2.recCGEPhyg8tf6DmM
BASIC_TIME_SERIES.2.recJ7pxumTQ6VXJfx

BASIC_TIME_SERIES.2.recpPvZA4naXDHFKi 
BASIC_TIME_SERIES.2.recXpDf5KZq94AyNi
BASIC_TIME_SERIES.2.recYQo7CIoQU5Uy6Y 
BASIC_TIME_SERIES.2.recZjYE8OF5hAlCBf
BASIC_TIME_SERIES.2.rec5UCQSQNyFvXePr
BASIC_TIME_SERIES.2.recZjYE8OF5hAlCBf 
BASIC_TIME_SERIES.2.recpPvZA4naXDHFKi
BASIC_TIME_SERIES.3.recm9iwNwjsG0EPOp

#### Materials

* Ipython notebook

#### Vocab / Concepts 

* Stationary
* Variance
* Dickey Fuller Test
* Differencing
	* Orders of differencing; 1st order, 2nd order, etc.
* Autocorrelation
* PACF - partial autocorelation function

#### Lesson Outline:

* What are time series?
* Stationarity: Checking for Constand Mean and Variance
	* After starting with an introduction to what is stationaryity, have students describe the difference between the initial constant mean and constant variance diagrams shown in order to solidify their working knowledge of the terminology.
	* Sorting Activity: Have students determine which graphs are and are not stationary, and explain why.
* Differencing
	* Explain differencing, and demonstrate it in practice
	* Have students try to difference the second dataset on their own
* Autocorrelation
	* Definition, connection to correlation....
* ACF and PACF Plots
	* Introduce the plots and how to interpret them
	* Have students discuss interpretation of these plot
