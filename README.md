# misc

## Summary

A personalized insurance product.

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
