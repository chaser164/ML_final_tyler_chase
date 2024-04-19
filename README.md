# PuppyFinder: A Dog Image Classification Project

*Tyler Tan & Chase Reynders*

## Setup

First, download the `archive.zip` file from (here)[https://www.kaggle.com/datasets/jessicali9530/stanford-dogs-dataset?resource=download] and place this .zip file in the same directory that contains `Tyler_&_Chase_Machine_Learning_Final_Project_implementation.ipynb`.

Next, create a python virtual environment from the `requirements.txt` folder like so:

1. From the directory containing the `.ipynb` file, call `python -m venv .venv`
2. Call `source .venv/bin/activate`
3. Call `pip install -r requirements.txt`

Now, you should be able to run all of the `.ipynb`'s chunks.

## TODO
- write / expand introduction at the top
- optimize hyperparameters further?
- consider: is transfer learning method the best option? & if not, let's turn to the imagenet repository
- more documentation, consider what else to include in MD sections of ipynb
- ensure portable setup, make this as plug-and-play as possible
- Attribute Kaggle sources properly (see Kaggle website specifying who must be cited)
- consider: different process for activating python virtual environment in windows? Is that something we need to explain here for adequate setup instruction?
- consider: is whippet 2349 misclassified?


## Helpful Sources

Pytorch transfer learning approach (quite helpful):
https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html
https://pytorch.org/hub/pytorch_vision_resnet/

Microsoft CNN image classification learning resource:
https://learn.microsoft.com/en-us/windows/ai/windows-ml/tutorials/pytorch-train-model

PyTorch classification tutorial:
https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html
