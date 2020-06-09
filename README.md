# Deploying-a-Sentiment-Analysis-Model
## Introduction
In this project a recurrent neural network will be constructed to determine the sentiment of a movie review using the IMDB dataset. You will create, train and deploy this model using Amazon's SageMaker service. In addition, you will deploy your model and construct a simple web app which will interact with the deployed model.
## Topics:
This project will cover several areas:
 - Machine learning
 - Natural language processing
 - RNN (LSTM, GRU)
 - Pytorch
 - SageMaker
 
The project can be extended to include the word2vec embedding (Skip Grams model, continuous-bag-of-words, negative sampling, etc):

## Deployment Instructions
The deployment project which you will be working on is intended to be done using Amazon's SageMaker platform. In particular, it is assumed that you have a working notebook instance in which you can clone the deployment repository.

- Clone the repository and navigate to the downloaded folder.

	git clone https://github.com/https://github.com/Mostafa-elgendy/Deploying-a-Sentiment-Analysis-Model.git
	cd Deploying-a-Sentiment-Analysis-Model
- Make sure you have already installed the necessary Python packages according to the README in the program repository.

- Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.

## Rquired Libraries
The list below represents main libraries and its objects for the project.

- Amazon SageMaker. (Build, train, and deploy a model)
- PyTorch (LSTM classifier)
