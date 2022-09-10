# DL-TransferLearning-cats-and-Dogs
> Transfer learning is an optimization that allows rapid progress or improved performance when modeling the second task. Transfer learning is the improvement of learning in a new task through the transfer of knowledge from a related task that has already been learned

## Data Collection
> This project uses kaggle API to source Cat and Dogs Dataset.

You should have a verfified account on kaggle, from there you dowdload kaggle.json file thatyou will query data with. 

Search for cat and dogs dataset and agree to terms of the competition and copy the API provided

## Installations
> `!pip install kaggle` but if your using google collab the requirement is already certified

 **configuring kaggle library**
 
`!mkdir -p ~/.kaggle`

`!cp kaggle.json ~/.kaggle/`

`!chmod 600 ~/.kaggle/kaggle.json`

Then call the call API

## Content

* [Deeplearning cat and Dogs](https://github.com/MutegiMk/DL-TransferLearning-cats-and-Dogs/blob/main/deeplearning%20Cats%20and%20dogs.ipynb): This jupyter notebook contains transfer learning workflow where I use a trained model from tensorflow_hub to predict a sample of 2000 images of cat and dogs from a collection of 25000 images

***Tools: sklearn, tensorflow, pandas, numpy, google colab patches, matplotlib***
  
