# Aviation Safety NLP: Topic Modeling and Classification

## Overview

This project applies Natural Language Processing techniques to analyze aviation safety reports from the ASRS database. The goal is to identify recurring safety patterns and automatically classify incident reports based on underlying causal factors.

## Problem Statement

Aviation safety reports contain valuable insights, but manual analysis is time consuming and inconsistent. This project explores how machine learning can be used to extract meaningful patterns and support data driven safety analysis.

## Methodology

* Text preprocessing (cleaning, tokenization, stopword removal)
* TF-IDF vectorization
* K-Means clustering for topic modeling
* Supervised classification model for categorizing reports

## Results

* Analyzed 1000+ aviation safety narratives
* Identified key safety themes in pilot training scenarios
* Built a classification model achieving approximately 85 percent accuracy

## Tech Stack

* Python
* Pandas
* Scikit-learn
* NLP techniques (TF-IDF, clustering)

## Files

* `asrs_topic_modeling.ipynb` → main analysis and modeling
* `asrs_topic_modeling_report.pdf` → detailed report and results

## Future Improvements

* Apply advanced NLP models such as BERT or LDA
* Improve classification performance with hyperparameter tuning
* Extend to real time decision support applications
