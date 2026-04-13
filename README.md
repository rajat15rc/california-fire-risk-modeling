# California Fire Risk Modeling

## What this project is about
This project explores whether daily environmental conditions can be used to predict fire occurrence in California.

The data combines station-level observations such as:
- region,
- date,
- evapotranspiration,
- precipitation,
- solar radiation,
- vapor pressure,
- temperature,
- humidity,
- wind,
- and soil temperature.

The goal is not only to classify whether fire is likely, but also to understand which combinations of conditions and which regions are most associated with fire activity.

## Why this matters
Fire risk is influenced by a combination of weather and environmental conditions rather than a single variable.

This repository studies that relationship in three stages:
1. exploratory data analysis,
2. predictive modelling,
3. interpretation of environmental combinations and regional similarity.

## Repository structure
- `California Fire Prediction_EDA.ipynb`  
  Exploratory analysis of the environmental variables, seasonal patterns, and regional fire distributions.

- `California Fire Prediction Modeling_CDA.ipynb`  
  Main modelling notebook, including preprocessing, class balancing, XGBoost classification, evaluation, and causal discovery analysis.

- `California Fire Prediction_FC and Everything else.ipynb`  
  Additional interpretation notebook, including feature-combination analysis, predicted fire probabilities, and region-similarity analysis.

- `Rajat Choudhary BGS PPT.pptx`  
  Presentation material related to the project.

## What the project does
This repository:
- cleans and preprocesses environmental station data,
- handles class imbalance,
- trains a fire-risk classifier,
- evaluates predictive performance,
- explores causal structure between variables,
- identifies environmental combinations with high fire rates,
- compares the similarity of regions based on their environmental profiles.

## What a non-technical reader should take away
This is not only a machine-learning classification project.

It is a project about understanding how environmental conditions relate to fire occurrence, and about making those relationships easier to interpret across seasons and regions.

## Important note
The notebooks currently expect an input dataset file (`all_conditions.csv`). To make the repository fully reproducible, that dataset or a small sample version should be added, along with setup instructions.
