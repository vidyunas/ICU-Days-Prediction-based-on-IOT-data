# VitalDB IOT data ICU days Prediction
The dataset contains information related to 6,388 surgical patients composed of intraoperative biosignals and clinical information. 
The biosignal data included in the 
dataset is high quality data such as  500 Hz waveform signals and numeric values at intervals of 1-7 seconds. 
More than 60 surgery related clinical information is also provided to help interpret the signals.

## Overview
This is a Jupyter notebook that predicts the Number of ICU days needed for each patient based on their Pre operative, intra operative and post operative status and paramters


## Description
The notebook uses machine learning techniques to build a model that predicts the ICU days required for each patients. T
he data includes information on anesthesia time, bmi, ASA Physical status classification, opertaion type, procedure, hemoglobin , ph, etc levels during each stage of operation. 
The notebook includes visualizations of the data, model training and testing, and a prediction .

## Requirements

You will also need to have the following Python libraries installed:

* pandas
* numpy
* matplotlib
* seaborn
* scikit-learn
* scipy

You can install these libraries using pip or conda.

In addition, we used BioBERT pre trained model for feature extraction from medical records.

## Contributing
This repository is open for contributions. If you find any issues or have any suggestions, feel free to create a pull request or open an issue.






