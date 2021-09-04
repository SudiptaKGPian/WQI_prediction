# WQI_prediction
Classification based machine learning models for prediction of ground water quality of the Indian Subcontinent

## Overview:

Keeping track of the water quality is of utmost important because water is the most resource for survival. Hence, the quality of water, especially the groundwater, has a direct impact on almost any domain starting from health, agriculture, food/dairy, industry and economy. Therefore, in this project, I have used supervised machine algorithms to build predictive classification models. The major motive was to do a comparative analysis of the few most widely used algorithms on the target data of groundwater. Also, to find out the top 6 parameters that are highly linked with the water quality measurement so that this can reduce the experimental burden of calculation of multiple parameters.

The dataset of experimentally collected samples were collected from publicly distributed data on the Government website. The cleaned dataset consisting of 2265 samples was used as the starting dataset for predictions. 

## Data collection:
Ground water quality data of India was collected from the Central Ground Water Board (CGWB).
Publicly disclosed data from 2010 to 2018 was used for this project.
Link: http://cgwb.gov.in/wqreports.html.

* **PS:** The collected data are available in the "datasets" folder.

## Requirements:
* Tested on Python 3.8.8 (but should work completely fine on Python 3.5+)
* Pandas
* Numpy
* Matplotlib
* Seaborn
* Imblearn
* SelectKBest
* ScikitPlot

## Stats:

**Accuracy scores:**
* Decision Tree:          94% (with all the features)  
* Random Forest:          96% (with all the features)  
* K-Nearest Neighbor:     86% (with all the features)  
* Support Vector Machine: 96.4% (with all the features)
* Support Vector Machine: 98% (after feature reduction, with only 6 features out of 13)

**Evaluation of the models was done by:**
* 5-fold cross validation
* ROC-AUC curve

## Resources for understanding the project:

* WQI Calculations: https://www.youtube.com/watch?v=HTkNmmMoUzE.
* https://www.researchgate.net/figure/Indices-used-in-the-calculation-of-water-quality-and-irrigation-water-quality_tbl1_329186453
* Research paper: Aldhyani, T. H., Al-Yaari, M., Alkahtani, H., & Maashi, M. (2020). Water quality prediction using artificial intelligence algorithms. Applied Bionics and Biomechanics, 2020.https://doi.org/10.1155/2020/6659314


