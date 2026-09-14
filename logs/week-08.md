# Week 8

**Dates:** 08-19 to 08-26

## Goals

The goal for this week was to begin building and evaluating a hybrid machine learning model.

1.Process the TNBC features through the pipeline: feature encoding → VQC → classical classifier/hybrid ML model.
2.Compare the performance of a classical machine learning model using Random Forest with a hybrid model using Logistic Regression.

## Approach and Implementation

I built upon the VQC code from the previous week, using the merged dataset containing the encoded features along with the harmonized dataset containing the remaining classical features. I utilized the code structure provided by Jaclyn and independently modified it to work with my specific datasets, features, and desired results. I then implemented the classical and hybrid approaches to compare their classification performance on the TNBC data.

## Results

The classical model performed better than the hybrid model in this experiment. The classical Random Forest model achieved an accuracy of 71.7%, while the hybrid model using Logistic Regression achieved an accuracy of 61.3% for TNBC classification. This comparison allowed me to evaluate how the quantum encoding and VQC pipeline performed relative to a classical machine learning approach.

## Notes

-the google colab week 12 notebook contains both the VQC and the hybrid ML model. 
