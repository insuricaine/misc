# misc

## Summary

A personalized short-term home insurance product for hurricane.

## Problem

 A few days before landfall of the disaster people realize they only have partial coverage of their home (e.g. flood insurance, natural disaster insurance). They want coverage against the impending disaster but no traditional insurance company will process their request fast enough nor want to cover them before the event. They can purchase emergency short-term insurance from Insuricane. After processing their insurance request through a webapp, we immediately determine how to hedge our position by automatically building a highly-correlated portfolio of insurance companies, CPGs, local real-estate holdings, etc.  

## Case Study

For PennApps we will build out a case study and backtest on one event: Hurricane Ike (2008). We will pretend it is September 10, 2008 at 1200 UTC; three days before landfall in Texas.

![ike data](present.png)

## Assumptions for the project

Hurricane either hits or misses their home.

## Description of Mockup

1. A front end where the user can input (1) how much insurance $ they want and (2) their address. Must have pretty visualization of storm.
2. A backend where
  (a) The expected damage (AKA probability of being hit)
  (b) A highly correlated portfolio (to the insurance) and the variance between the house an the portfolio, sigma. Then return the lump sum premium.
  
3. User accepts the insurance and uses DocuSign to sign documents and enter payment info.

## Division of Labour

* Andrew - by Saturday: write a python function risk() that returns the percentage chance that the hurricane is going to hit their house.
* Jacob - by Sunday: write a python function asset() that returns a highly correlated portfolio and the variance sigma
* Jimmy/Cam - front end

## Packages
* QGIS
* https://developers.google.com/maps/documentation/geocoding/intro#geocoding
* https://www.nhc.noaa.gov/gis/
* http://kepler.gl/#/
* https://gis.stackexchange.com/questions/274381/installing-qgis3-on-mac
