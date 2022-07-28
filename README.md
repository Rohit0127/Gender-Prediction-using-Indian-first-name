# Gender-Prediction-using-Indian-first-name

The aim of this project is to predict the gender of an Indian person based on their first name. The dataset used is first pre-processed, which is followed by feature extraction. Then several models are trained using the generated data, and are tested to check the performance.

## Dataset

A freely available dataset from Kaggle has been used here. The dataset consists of following fields:
1) Name: Name of the person in english language
2) Gender: Gender of the person. ‘m’ for male and ‘f’ for female.
3) Race: Race of the person (Indian)

There are 30,227 names in the dataset, of which, 14,845 are male and remaining 15,382 are females. Intially male and female names are in separate datasets.

## Pre-processing steps
1) Combining both datasets and removing repetitions. 
2) Removing first name and salutations from the names.
3) Extracting the first name.
4) Encoding male as '1' and female as '0'.



