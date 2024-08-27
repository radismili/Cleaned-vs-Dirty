# Kaggle competition: Cleaned-vs-Dirty V2

Dataset contain 20 clean and 20 dirty plates images in the train dataset and hundreds of plates in the test dataset. It is located on the Kaggle website and is part of the Kaggle competition "Cleaned vs Dirty V2".
Dataset link: https://www.kaggle.com/competitions/platesv2/overview

*File descriptions*
- plates.zip - dataset with train and test folders
- sample_submission.csv - a sample submission file in the correct format

*Data fields*
- id - id of an image from the test folder. If image name is 0123.jpg its id will be 0123
- label - predicted label. One of: dirty, cleaned

The goal is to train a model who can classify if a plate is clean or dirty. 
I used Transfer Learning, VGG16 as a base model.
