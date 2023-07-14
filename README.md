# Usage of Machine Learning Techniques for Prediction of the Remaining Useful Lifetime of Electric Motors

**Author:** Menéndez González, Alonso  
**Tutor:** Granda Candás, Juan Carlos  
**Co-tutor:** Magadan Cobo, Luis  

**Date:** 13th of July, 2023

## Introduction

This bachelor thesis will study the different techniques and approaches to predictive maintenance by analyzing different types of bearing failures in electric motors. For this purpose, the vibration data of bearings will be cleaned and analysed to obtain statistics about each stage of its lifetime, as well as the study of different metrics and machine learning techniques to define what a healthy bearing is.

## Repository Structure

This repository contains a part of the files that were generated during the development of this bachelor thesis, and is structured as follows:

- `Approach 1 - Time domain`: This directory contains the `PreliminaryOverview` and `FirstApprox` notebooks, with the first steps done to familiarize with the tools and the necessary functions to compute the characteristics of the IMS dataset, including the RMS. There are also the `timeRMS-testX-velocity.csv` files, with the computed velocity RMS for each test set.

- `Approach 2 - Frequency domain`: This directory contains the `SecondApprox` notebook, with the functions used to perform the FFT transformation, as well as the analyses done with Select K Best, PCA and t-SNE. The `loadings-PCA-testX-CHY-fixed.csv` files are also in this folder, which contain the loadings of PCA for a 95% explained variance.

- `Approach 3 - Machine Learning`: This directory contains the last notebook, `ThirdApprox`, which analyses the results from the previous notebook, contained in the file `nimbus-test3-CH3-fixed`, with the use of machine learning techniques.
