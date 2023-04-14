# Revolutionizing Agriculture: Enhancing Agriculture Planning with Neural Networks Rainfall Predictions
## Moto:
* To predict whether it will rain tomorrow or not using kaggle australian dataset 
* Used Neural networks algorithms to predict the rainfall

## Abstract:
Neural networks [ BPNN,MLP,RBF,RNN] have been used to create different models which predicts the daily rainfall. The input data set comprises of the parameters affecting rainfall such as minimum and maximum temperature, wind speed and humidity at different timings, evaporation, RainToday, RainTomorrow. The performance of all the models assessed by comparing their results using evaluation metrics such as Accuracy, Cohen’ Kappa score etc., and subsequently the conclusion was drawn as BPNN outperfomed other models

## Tech stack:
* Front-End: HTML, CSS, Bootstrap
* Back-End: Flask
* IDE: Jupyter notebook, VS code
 
## To run this app:
* First create a virtual environment by using this command:
* conda create -n myenv python=3.6
* Activate the environment using the below command:
* conda activate myenv
* Then install all the packages by using the following command
* pip install -r requirements.txt
* Now for the final step. Run the app
* python app.py

## Model creation:

* 4 models have been used to train the models
* such as BPNN,MLP,RBF,RNN
* Among these 4 models BPNN performed well with 86% accuracy and weighted F1 score of 85% 
* Different evaluation metrics used were accuracy, Weighted F1 score, kappa score, precision, recall
