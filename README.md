# DS9000-FlightDelayPrediction

## Data set
The dataset couldn't be uploaded to GitHub due to size limits, but a link is provided below. The dataset can be reproduced by following the data preprocessing steps outlined here.
https://www.kaggle.com/datasets/robikscube/flight-delay-dataset-20182022/data

## Data Preprocessing
1. Data was converted to smaller datatypes in the EDA file, and unnecessary columns were removed. All steps are clearly defined in the EDA file.
2. When the dataset was loaded for the modelling part, it was discovered to be corrupted due to the pandas to_parquet method not supporting float16. The EDA file was revisited, and those columns were converted to int16 for better support and efficiency. This step was performed at the end of the EDA file and is documented there.
3. The new dataset file was imported, and additional preprocessing was performed for modelling. Everything is well documented in the Jupyter file.
4. After all preprocessing, the dataset is ready for machine learning.

## More details can be found in the Notebooks!
