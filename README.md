# Malaria-Detection-Image-Classification
We have a collection consisting of 19290 blood-cell images out of which 50% are Maleria-Parasite affected cells and 50% are healthy. 
We have to build a classifier model which can classify the cells based on their characteristics. 
We have a .CSV file (train.csv) which contains the title of each image in the column filename and the column label tells us which class the image blongs to, there are two classes- malaria & healthy.
We used accuracy_score as an evaluation metric as the data was of balanced class.
First, Wrote a function to read the images from the folder based upon the filename column in the dataset provided
Then we did some basic EDA and looked at the properties and the kind of images we have in the data.
Resized each image into 128X64 pixels
Then extracted hog features from the image and stores in an array
Trained the classifier on the Training Hog-features and Training Labels
Predicted the reulsts on training and test data.
