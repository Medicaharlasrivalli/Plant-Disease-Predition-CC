Motivation:

The goal of Plant Disease Classification using DenseNet121 is to create a reliable and effective approach for identifying and categorising plant diseases. This system's goal is to assist in the early detection of plant diseases, which is essential for avoiding widespread harm and minimising crop losses. Particularly in poorer nations, plant diseases can significantly affect agricultural output and food security. To stop the spread of plant diseases and to lessen their negative economic and social effects on farmers and local communities, it is crucial to identify them as soon as possible. The identification and classification of plant diseases can be automated with the aid of computer vision and machine learning techniques, which will make the procedure quicker and more precise. With the use of DenseNet121, we can create a robust and trustworthy system for classifying plant diseases that will aid agronomists and farmers in identifying and controlling plant diseases more successfully, thereby increasing agricultural yields and ensuring food security

Plan of the Project:

Model Creation

Data Collection: Collection of the Required Plant Disease Data which we will use to train and test our Machine Learning Model.
Data Preprocessing:Data Preprocessing can be done by Data Cleaning , Data Transformation and Data Reduction.
Data Cleaning: Found the missing data and filled it, unnecessary data will be removed and the data with the noise will be removed by regression or clustering
Data Transformation: In this we are transforming the data using Batch-Normalisation.
Data reduction:Reduce the data based on aggregation.
Extracting the Features and Training the Data:
Extracted the features of the DataSet.
Trained the data and generated a model using the DenseNet.
Testing Data:The Prediction is successful Identifying the disease of the plant image.
Web App:

Using the model generated using the machine learning algorithm we will create a flask application where we can upload the image so the application can predict the disease caused to the Plant.

