# Beijing PM2.5 Forecasting Challenge

Air pollution is a critical global issue, and PM2.5 concentrations are among the most harmful pollutants due to their ability to penetrate deep into the lungs and even enter the bloodstream[1]. Accurate forecasting of PM2.5 concentrations is essential for timely public health interventions, such as issuing air quality advisories and enacting pollution control measures to reduce exposure and protect vulnerable populations[2].

This project focuses on the Beijing PM2.5 Forecasting Challenge, which aims to predict PM2.5 concentrations in Beijing using historical air quality and weather data. Several experiments are made while tuning parameters to achieve better results.

The primary goal of this challenge is to gain hands-on experience with real-world time series forecasting while optimizing the Root Mean Squared Error (RMSE).

## Repository structure

air_quality_forecasting_ML/
│── train/                    # Contains the training dataset

│── test/                     # Contains the test dataset

│── notebook/                 # Contains the Jupyter/Colab notebook for model development

│── results/                  # All submission files

│── README.md                 # Project documentation


## Instructions for reproducing results

1. **Download the Datasets**
  
The training dataset is located train/ folder (air_quality_forecasting_ML/train/) while

The test file is located test/ folder (air_quality_forecasting_ML/test/).

2. **Open the Notebook**

The Colab notebook, which contains the full workflow (preprocessing, model training, evaluation, and saving), is located in the notebook/ folder (air_quality_forecasting_ML/notebook/).

You can download the notebook or open it in Google colab by clicking on the link on the notebook.

3. **Make a Copy of the Notebook (Recommended)**

If using Google Colab, before making any changes, go to File → Save a copy in Drive. This will allow you to edit the notebook while keeping the original version intact.

**4. Upload the Dataset**

Upload the train and test datasets to the file browser in Colab.

Alternatively, upload the datasets to your Google Drive and mount your drive to access them. See the second code cell in the notebook for instructions.

5. **Run the code**

Execute the notebook step by step to preprocess the data, train the model, and evaluate results.

**Suggestions**

You can experiment by either checking parameters, model architecture or different models.
