[//]: # (Image References)

[image1]: ./images/sample_dog_output.png "Sample Output"

# Dog breed classification App


## Project Overview

This project involves the implementation of an image classification code using CNNs on a dog breeds dataset. Given an image of a dog, the algorithm will identify an estimate of the dog’s breed. If supplied an image of a human, the code will identify the resembling dog breed.  

![Sample Output][image1]

## Data

1. Download the [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip).  Unzip the folder and place it in the repo, at location `path/to/dog-project/dogImages`.  The `dogImages/` folder should contain 133 folders, each corresponding to a different dog breed.
2. Download the [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz).  Unzip the folder and place it in the repo, at location `path/to/dog-project/lfw`.  If you are using a Windows machine, you are encouraged to use [7zip](http://www.7-zip.org/) to extract the folder.

Using wget you can run this code and the data will downloaded:

```
!wget -qq https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip
!unzip -qq dogImages.zip
!rm dogImages.zip
!wget -qq https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip
!unzip -qq lfw.zip
!rm lfw.zip
!rm -r __MACOSX
```




Technologies used in this folder:

* Python, numpy
* Pytorch
* Convolutional Neural Networks (CNN)
* jupyter notebook, anaconda

## Data
~~~~~~~
!wget -qq https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip
!unzip -qq dogImages.zip
!rm dogImages.zip
!wget -qq https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/lfw.zip
!unzip -qq lfw.zip
!rm lfw.zip
!rm -r __MACOSX

~~~~~~~
