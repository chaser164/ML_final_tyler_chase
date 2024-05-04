# PuppyFinder: A Dog Image Classification Project

*Tyler Tan & Chase Reynders*

## Setup

First, download the `archive.zip` file from (here)[https://www.kaggle.com/datasets/jessicali9530/stanford-dogs-dataset?resource=download] and place this `.zip` file in the same directory that contains `Tyler_&_Chase_Machine_Learning_Final_Project_implementation.ipynb`. Be sure that it is named `archive.zip`. No need to unzip it yourself; the notebook will take care of this for you in the pre-processing step.

Next, we recommend creating a python virtual environment by running `python -m venv .venv` from the directory containing the `.ipynb` file. We suggest you do this so that the pip installs are not installed into your global python environment.

Be sure to choose the virtual environment you just created as the `.ipynb` file's selected environment.

Before running all chunks, note the second code chunk in the notebook. `use_old_model` is set to `True` in order to give you a brief demo of our already-trained model. If you wish to train a new model (which in our experience took a few hours), please set this boolean to `False`.

Now, you should be able to run all of the `.ipynb`'s chunks. If prompted to do so, install the `ipykernel` packages.

Note: you likely won't run into this, but we found that installing the `ipykernel` packages only works when pip3 is aliased to pip.

## TODO
- optimize hyperparameters further?
- consider: is transfer learning method the best option? & if not, let's turn to the imagenet repository
- more documentation, consider what else to include in MD sections of ipynb
- ensure portable setup, make this as plug-and-play as possible
- consider: is whippet 2349 misclassified?


## Helpful Sources for this project:

Pytorch transfer learning approach (quite helpful):
https://pytorch.org/tutorials/beginner/transfer_learning_tutorial.html
https://pytorch.org/hub/pytorch_vision_resnet/

Microsoft CNN image classification learning resource:
https://learn.microsoft.com/en-us/windows/ai/windows-ml/tutorials/pytorch-train-model

PyTorch classification tutorial:
https://pytorch.org/tutorials/beginner/blitz/cifar10_tutorial.html
