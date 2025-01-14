# Adikara 2024 Data Description

### Overview
The data used in this project consists of food price index data from several countries. Participants are provided with data to build a model. The model will be used to predict food prices for a specific country in a given year and month.

Participants are not allowed to use any data other than the provided dataset.

1. ```train_adikara2024.csv```  
   The main data file used for training models. This file contains labeled data necessary for building and training machine learning models.

2. ```test_adikara2024_unlabeled.csv```  
   The data file used for prediction. This file does not include labels and is intended for testing the performance of trained models by making predictions.

3. ```sample_submission_adikara2024.csv```  
   A sample file that demonstrates the expected format for submission. It provides an example of how predictions should be organized for evaluation.

---

### Dataset Column Descriptions
- **id**: A unique identifier for each observation.
- **Country**: Name of the country.
- **Year**: The year when the data was collected.
- **Month**: The month when the data was collected.
- **FoodPriceIndex**: The food price index (this is the target column to be predicted).
  
---

### Evaluation Metric
Symmetric Mean Absolute Percentage Error (sMAPE) is the evaluation metric used. It measures the average absolute error as a symmetric percentage.

---
