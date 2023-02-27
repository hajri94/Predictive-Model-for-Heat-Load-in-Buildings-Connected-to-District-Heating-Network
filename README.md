# Predictive Model for Heat Load in Buildings Connected to District Heating Network
# Project overview
District Heating (DH) systems operated reliably over decades and provided a relevant share of energy to households across Europe. Currently, 12% of Europe's heating energy to buildings is delivered by District Heating Networks (DHNs), with more than 6000 systems serving around 60 million citizens. Moreover the market shares for District Heating can be increased to 30% in 2030 and 50% in 2050 by introducing renewables and waste heat in the supply [1]. There are increasing variations in the system due to lower specific energy loads and intermittent renewable energy sources which raise the need for more accurate characterization and prediction of heat loads in buildings to ensure effective operation of these systems.

In this work we investigate the heat load patterns in one building using multi-step forecasting model based on **Segmented Auto Regressive Models (S-ARX-MLR)**. In other word we combine the Multivariate Linear Regression models (to capture physical dependencies) with Auto Regressive models (to deal with energy storage across data segments) and Integration features (to correct model inaccuracies), into an accurate and reliable regression model used in time series forecasting.
# Table of Contents
1. [Project Overview](#Project-Overview)
2. [Installation](#Installation)
3. [Data Sources](#Data-Sources)
4. [Data Preprocessing](#Data-Preprocessing)
5. [Load Assessment & Graphic Exploration](#Load-Assessment-&-Graphic-Exploration)
6. [Model Evaluation To characterize The Heat Load](#Model-Evaluation-To-characterize-The-Heat-Load)
7. [Model Optimization to Predict the Heat Load](#Model-Optimization-to-Predict-the-Heat-Load)
8. [Conclusion](#Conclusion)
# Installation
We clone the github repository in Google Colaboratory ([Google-Colab](https://colab.research.google.com)). A hosted jupyter notebook service that allow us to  write and execute arbitrary code through browser.  
## Step1 : 
Go to **File** ==> **Open Notebook** 

<img src="https://user-images.githubusercontent.com/82321097/221584844-62e71e5a-3740-47eb-a992-b902dc987463.png" width="100" height="100">



