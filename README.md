![IronHack Logo](https://s3-eu-west-1.amazonaws.com/ih-materials/uploads/upload_d5c5793015fec3be28a63c4fa3dd4d55.png)

# Project: Statistical Analysis

## Project aim ✔

The aim of this project is to use a personal dataset containing all my bike rides (with geospatial and biometric data) to answer several questions:

**1.** What variables affect caloric expenditure the most when I'm cycling?
**2.** Can this caloric expenditure be accurately predicted for any given route?
**3.** Are races and normal rides significantly different data-wise? In which ways?


---


## Setup & environment ⚙

This project has been created and run using **Python 3.8.8**, and I'm aware that earlier versions could potentially generate some conflicts, specially when parsing *gpx* files or displaying them on a map via **Selenium**.

The project is structured in such a way that anyone with a **SportTracks** account and some riding activity can easily replicate its results.

All necessary libraries are included in the *statistical-analysis* notebook. 


---


## Internal structure 📚

The project is structured into the following sections:

1. Data wrangling.
2. Data exploration.
3. Data visualization.
4. Prediction: Linear Regression and Multiple Linear Regression.
5. Prediction: model optimization with *Sklearn*.
6. Hypothesis testing.
7. Conclusions.
8. Bonus: parsing and mapping of *gpx* files.


---


## Notes and warnings ⁉

My statistical skills have expanded quite a bit since this project was finished, and it's therefore expected to find some flaws in it. For example, data normalization wasn't used, nor was the small *race* sample subjected to oversampling, which could have potentially improved the accuracy of some results.


---
