# Shark-Recognition-DL

(this project is under development)

## OVERVIEW
This project consists of a deep learning model to identify sharks of 3 different types: 'great white', 'hammerhead' and 'tiger'. It will not perform well with any other species of shark.

## STRUCTURE

### Model_Building.ipynb
The file 'Model_Building.ipynb' is a Jupyer Notebook used to build the model. 
Data was obtained through the Bing Image Search API and randomly divided into a training and a validation set.
Following the data gathering stage, an initial model was trained with the purpose of providing aid in the data cleaning process. After some data cleaning, a final model was trained and extracted into the 'export.pkl' file.
The training used the already pre-trained 'resnet' model.
The accuracy of the final model was of 88.70% for images of the 3 types of shark tested.
All methods used for the design of this model were extracted from the 'fastai' library.

### export.pkl
This file consists of the final trained model for shark recognition.

### WebApp.ipynb
This simple web application consists of ipy widgets and has the goal of providing a way for any user with a wifi connection to test the model by uploading a picture of a shark and eceiving the model's prediction. Voila was used to help access the web app.

### requirement.txt
File used in deployment to provide libraries used in the web app.

## TODO
The next step in this project is to deploy the web application. This is to be done using Voila with conjuncture with a deployment service (myBinder or Heroku).


