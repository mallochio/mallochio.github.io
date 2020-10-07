---
layout: page
title: Credit risk forecasting for mortgage loans
description: Creating multi-stage credit risk prediction pipelines for mortgage loans
img: /assets/img/creditrisk.jpg
importance: 2
---

*Note: This project was done at Ernst and Young, Amsterdam.*

Here's a [link](https://github.com/mallochio/neuroCredit) to the code repository, and a [link](https://github.com/mallochio/neuroCredit/blob/master/report/NeuroCRF.pdf) to the report.

Abstract: We propose a novel method for predicting defaults on mortgage loans. The method utilizes a combination of Fuzzy C-means (FCM) clustering and an Adaptive Neuro-Fuzzy Inference System (ANFIS) in order to produce accurate and intuitive predictions. A SMOTE technique was used to increase the number of underrepresented data in the dataset. A range of dimensionality reduction techniques were investigated for the project. The best results were achieved by using Principal Component Analysis (PCA) or sparse PCA coupled with the FCM and ANFIS network. Using sparse PCA yielded the highest sensitivity of 99.99\% and using PCA gives the highest precision of 99.95\% from cross-validation.