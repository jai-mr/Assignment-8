* Repository github url : https://github.com/jai-mr/
* Assignment Repository : https://github.com/jai-mr/Assignment-8
* Submitted by : Jaideep Rangnekar
* Registered email id : jaideepmr@gmail.com

## Objective to achieve the use of RESNET18 model on the CIFAR-10 dataset:
1. Base repository for use of resnet18 : https://github.com/kuangliu/pytorch-cifar
2. Extracted the ResNet18 model from this repository and added  to repo. 
3. Use the below py code to train ResNet18 on Cifar10 from packages 
      i. data.py
     ii. Net.py
    iii. summary.py
     iv. train.py
      v. test.py
     vi. plot.py
4. Accuracy Details
    Training Accuracy : 95.66 %
    Test Accuracy     : 88.86%   
5. Class wise accuracies
    Accuracy of plane : 87 %
    Accuracy of   car : 95 %
    Accuracy of  bird : 80 %
    Accuracy of   cat : 80 %
    Accuracy of  deer : 92 %
    Accuracy of   dog : 85 %
    Accuracy of  frog : 93 %
    Accuracy of horse : 90 %
    Accuracy of  ship : 91 %
    Accuracy of truck : 94 %


## Jupyter Notebook File reference executed in Colab
[https://github.com/jai-mr/Assignment-8/blob/master/08_CodeFinal.ipynb](https://github.com/jai-mr/Assignment-8/blob/master/08_CodeFinal.ipynb)

## Training/Test - Loss & Accuracy Curve
[https://github.com/jai-mr/Assignment-8/blob/master/images/accuracy.png](https://github.com/jai-mr/Assignment-8/blob/master/images/accuracy.png)

## Test vs Train Accuracy
[https://github.com/jai-mr/Assignment-8/blob/master/images/testvtrain.png](https://github.com/jai-mr/Assignment-8/blob/master/images/testvtrain.png)

## Mis-Classified Images
[https://github.com/jai-mr/Assignment-8/blob/master/images/misclassification.png](https://github.com/jai-mr/Assignment-8/blob/master/images/misclassification.png)

## CIFAR10
Cifar10 is a classic dataset for deep learning, consisting of 32x32 images belonging to 10 different classes, such as dog, frog, truck, ship, and so on. Cifar10 resembles MNIST — both have 10 classes and tiny images. 

## RESNET
A residual network, or ResNet for short, is an artificial neural network that helps to build deeper neural network by utilizing skip connections or shortcuts to jump over some layers. Skipping helps build deeper network layers without falling into the problem of vanishing gradients.

There are different versions of ResNet, including ResNet-18, ResNet-34, ResNet-50, and so on. The numbers denote layers, although the architecture is the same.

To create a residual block, add a shortcut to the main path in the plain neural network, as shown in the figure below.

[https://i.imgur.com/0F06Psz.png](https://i.imgur.com/0F06Psz.png)



References:

[1. introduction-to-resnet](https://www.pluralsight.com/guides/introduction-to-resnet)

[2. Base github repository](https://github.com/kuangliu/pytorch-cifar)

[]()
