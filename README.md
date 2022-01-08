# Neural Networks & Deep Learning

> CZ4042 Neural Networks & Deep Learning \
> School of Computer Science and Engineering \
> Nanyang Technological University

This repository consists of CZ4042 Assignment 1, which is composed of the following problem sets:

## (A) Music Genre Classification

<b>AIM:</b> Perform music genre classification by predicting the genre label for a given audio file.

<b>DATASET:</b> GTZAN dataset
* ```features_30_sec.csv```
* 1000 audio tracks, 30 seconds each
* Audio tracks preprocessed into 57 features
* Genres (10 labels): blues, classical, country, disco, hip-hop, jazz, metal, pop, reggae and rock
* 1 pattern: filename + audio length + 57 features + label/genre

## (B) HDB Price Prediction

<b>AIM:</b> (i) Perform retrospective prediction of HDB housing prices (resale_price), (ii) Identify the most important features that contributed to the prediction (Recursive Feature Elimination)

<b>DATASET:</b> Publicly available data on HDB flat prices in Singapore, obtained from data.gov.sg on 5th August 2021
* ```hdb_price_prediction.csv```
* Original feature set modified with other datasets to add informative features, as outlined in ```Assignment1.pdf```
