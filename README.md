# TrafficSignClassifier

This project uses the traffic signs from the [German traffic sign dataset](http://benchmark.ini.rub.de/?section=gtsrb&subsection=dataset) to train a classifier. The classifier uses a convolutional neural network based on the Lenet architecture first described by Yann Lecun in this [paper](http://yann.lecun.com/exdb/publis/pdf/lecun-98.pdf).

The Traffic_Sign_Classifier.ipynb jupyter notebook explains the various steps taken to implement the network starting with the training, validation, and test image datasets and shows the results obtained by running it. A Traffic_Sign_Classifier.html has also been included.

## Packages needed for Python 3
* Pickle
* Numpy
* Pandas
* MatplotLib
* random
* Tensorflow
* OS
* PIL


The network was trained on using AWS GPUs. It may take a long time to run on a machine without GPU support.

## View/run the project

`jupyter notebook Traffic_Sign_Classifier.ipynb`

Run all cells.

## Final results of the project

* Training set accuracy of **99.9%**
* Validation set accuracy of **97.0%**
* Test set accuracy of **95.1%**

The discussion of the results in the Jupyter notebook includes suggestions for improving on these.
