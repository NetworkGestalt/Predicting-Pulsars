# Predicting Pulsars with Machine Learning: A Cost-Sensitive, Clusterthen-Classify Approach (__R__)

## Description

LSE Summer School 2022 - ME315: Machine Learning in Practice - Final Project __in R__.

## Abstract

The classification of pulsars comes with many challenges. Proper radio signal metrics
are needed to support the classification pipelines that flow from them. This analysis
discusses some of these challenges to contextualize supervised (binary classification)
and unsupervised (clustering) machine learning approaches to the Pulsar
classification problem, as well as several metrics that can be used to evaluate them. It
emphasizes a cost-sensitive approach, weighing sensitivity and specificity with the
relative costs of false negatives and false positives. Finally, it combines the highestperforming clustering and classification models into two Cluster-then-Classify models for different cost contexts. Both combined models have higher accuracy than their
stand-alone counterparts, due to synergies between features and cluster classes born
from unknown patterns. The analysis end with a motivation for ongoing pulsar classification.

## Table of Contents

* [Installation](#installation)
* [Project Report](#report)
* [Project Source Code](#source-code)

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

## Report

[Predicting Pulsars Report.pdf](https://github.com/NetworkGestalt/Predicting-Pulsars/files/10339398/Predicting.Pulsars.Report.pdf)

## Source Code

[Predicting Pulsar Source.txt](https://github.com/NetworkGestalt/Predicting-Pulsars/files/10339408/Predicting.Pulsar.Source.txt)
