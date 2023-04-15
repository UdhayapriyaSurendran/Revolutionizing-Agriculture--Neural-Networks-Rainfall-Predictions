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

## Result

* CASE-1: When tomorrow is rainy:
* INPUT:
* ![Screenshot 2023-04-14 223416](https://user-images.githubusercontent.com/126506928/232222956-a8655def-180f-4494-8853-b9ed04eed37e.png)
* OUTPUT:
* ![Screenshot 2023-04-14 213721](https://user-images.githubusercontent.com/126506928/232222985-6fc910c3-0569-4502-a6a9-e1625ef7623a.png)

* CASE-2: When tomorrow is sunny:
* INPUT:
* ![Screenshot 2023-04-14 223048](https://user-images.githubusercontent.com/126506928/232223067-1fef6edb-0368-4a10-ace7-f7831b012222.png)
* OUTPUT:
* ![Screenshot 2023-04-14 222432](https://user-images.githubusercontent.com/126506928/232223081-26e50f3d-e9ec-4d38-8176-711ba480bfaa.jpg)



