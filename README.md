[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"

# Dog breed classification App


## Project Overview

This project involves the implementation of an image classification code using CNNs on a dog breeds dataset. Given an image of a dog, the algorithm will identify an estimate of the dog’s breed. If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

### Technologies used:

* Python, numpy
* Pytorch
* Convolutional Neural Networks (CNN)
* Transfer learning: VGG16, Resnet50
* jupyter notebook, anaconda

## Data

1. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
2. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`. If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder.

Also, the data can be downloaded using wget:

```
!wget -qq https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip
!unzip -qq dogImages.zip
!rm dogImages.zip
!wget -qq https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip
!unzip -qq lfw.zip
!rm lfw.zip
!rm -r __MACOSX
```

## Installation

Using [Anaconda](https://www.anaconda.com/products/individual), run the following lines of code:

1. Create an enviroment:
```
conda create -n dog_app python=3.6
conda activate dog_app
```

2. Install pytorch and torchvision:
```
conda install -c pytorch pytorch
conda install -c pytorch torchvision
```

3. Install a few required packages, which are specified in the requirements text file (including OpenCV):
```
conda install --file requirements.txt
or
pip install -r requirements.txt
```
