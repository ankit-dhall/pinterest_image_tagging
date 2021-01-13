# Pinterest Image Tagging
### Incorporating Deep Learning to Improve User-Experience

This repository houses the source code and results of developing an image classification model to enable Pinterest image tagging suggestions


## Table of Contents

- [Project Overview](#projectoverview)
- [Data Description](#datadescription)
- [Technical Overview](#technicaloverview)
- [Results](#results)

***

<a id='projectoverview'></a>
## Project Overview

This project aims to implement an image classification model using transfer learning, aimed at providing users on Pinterest with category suggestions for any images they might upload. 

This implementation would help users identify and categorize their images more effectively and efficiently, thus improving user experience and engagement on the platform.

The project also implements LIME analysis in order to help explain and understand model predictions.

<a id='datadescription'></a>
## Data Description

The dataset used, is a collection of over 9,000 images belonging to the 8 most popular categories under which image are uploaded on Pinterest.

These images were scrapped from Pinterest in accordance with the robots exclusion standard.
The dataset using the link referred here [Dataset Link.txt](https://github.com/ankit-dhall/pinterest_image_tagging/blob/main/dataset/Dataset%20Link.txt)

Further, the dataset was manually tagged and organized into training, validation, and test sets for model development.

<a id='technicaloverview'></a>
## Technical Overview

The project works on building a relevant model by working on various aspect including explanation of model predictions, performance analysis, and time-taken for prediction.
4 transfer learning models were used in order to compare results and analyze the model performance to complexity/size.

The project has been divided into various steps which include:
* Data Scrapping, Tagging, and Organization
* Training Models
  * Basic Ann Model Training [Basic ANN Model.ipynb](https://github.com/ankit-dhall/pinterest_image_tagging/blob/main/Basic%20ANN%20Model.ipynb)
  * Basic CNN Model Training [Basic CNN Model.ipynb](https://github.com/ankit-dhall/pinterest_image_tagging/blob/main/Basic%20CNN%20Model.ipynb)
  * CNN Transfer Learning Models [CNN - Transfer Learning.ipynb](https://github.com/ankit-dhall/pinterest_image_tagging/blob/main/CNN%20-%20Transfer%20Learning.ipynb)
* Testing Model Performance
  * Testing Transfer Learning Models [Test Model.ipynb](https://github.com/ankit-dhall/pinterest_image_tagging/blob/main/Test%20Model.ipynb)
  * K-Fold Cross Validation [K-Fold Cross Validation.ipynb](https://github.com/ankit-dhall/pinterest_image_tagging/blob/main/K-Fold%20Cross%20Validation.ipynb)
  * Timing Model Predictions [Timing Models.ipynb](https://github.com/ankit-dhall/pinterest_image_tagging/blob/main/Timing%20Models.ipynb)
* LIME Analysis - Model Explainability [LIME Analysis.ipynb](https://github.com/ankit-dhall/pinterest_image_tagging/blob/main/LIME%20Analysis.ipynb)

<a id='results'></a>
## Results

The model training snapshots were saved and used in testing and LIME analysis. These snapshots are not uploaded in this repository due to their large file size.

A detailed analysis report including details on data collection, methodologies used, performance results, and hyperparameter tuning can be referred to here. [Project Report.pdf](https://github.com/ankit-dhall/pinterest_image_tagging/blob/main/Project%20Report.pdf)