# Predicting Pulsars with Supervised and Unsupervised Learning: A Cost-Sensitive, Cluster-then-Classify Approach (__R__)

## Description

Captsone project code and final report for the 2022 LSE Summer School course "ME315: Machine Learning in Practice".

## Table of Contents

* [Abstract](#abstract)
* [Installation](#installation)
* [Project Report](#project-report)
* [Project Code](#project-code)

## Abstract

The classification of pulsars comes with many challenges. Proper radio signal metrics
are needed to support the classification pipelines that flow from them. This analysis
discusses some of these challenges to contextualize supervised (binary classification)
and unsupervised (clustering) machine learning approaches to the Pulsar
classification problem, as well as several metrics that can be used to evaluate them. It
emphasizes a cost-sensitive approach, weighing sensitivity and specificity with the
relative costs of false negatives and false positives. Finally, it combines the highest performing clustering and classification models into two Cluster-then-Classify models for different cost contexts. Both combined models have higher accuracy than their
stand-alone counterparts, due to synergies between features and cluster classes born
from unknown patterns. The analysis end with a motivation for ongoing pulsar classification.

## Installation

Required libraries (__R__): 

1. RColorBrewer
2. tidyverse
3. Corrplot
4. MASS
5. InformationValue
6. pROC
7. caret
8. class
9. mclust

## Project Report

[Predicting Pulsars - Cost-Sensitive, Cluster-then-Classify.pdf](https://github.com/NetworkGestalt/Predicting-Pulsars/files/10347621/Predicting.Pulsars.-.Cost-Sensitive.Cluster-then-Classify.pdf)

## Project Code

[Predicting Pulsars Code (RMD File)](https://github.com/NetworkGestalt/Predicting-Pulsars/blob/main/Pulsar.Rmd)

[Predicting Pulsars Code (Text File)](https://github.com/NetworkGestalt/Predicting-Pulsars/files/10339408/Predicting.Pulsar.Source.txt)
 


