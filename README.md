# kNN Classifier on Python

The purpose of this package is to recognize handwritting number by using a kNN Classifier

### Organization

This Package is organized with 3 folders :
- [/script](https://github.com/Palpale/knnClassifier/tree/master/script) : python scripts for classification, recognition and ploting graph
- [/mnist](https://github.com/Palpale/knnClassifier/tree/master/mnist) : the MNIST raw data (.csv) with training images, training labels, test images, test labels
- [/result]() : the result data used to accelerate the analyze because of the computation time (data of test's 100 nearest images from training)

In order to see how work the kNN classifier you have to open knn.py. 
For analyzing the result for different k and all the data set (10k images) you should run plot.py

### Librairies dependences

You need to have numpy, and matplotlib on you computer. For that :

```sh
$ sudo apt-get install python-numpy python-scipy python-matplotlib
```
In order to execute python script:
```sh
$ cd script
$ python knn.py
$ python plot.py
```
