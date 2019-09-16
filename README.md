# LeNet5 on CIFAR10 dataset

A notebook which explores hyper parameter optimisation and performance of LeNet5 CNN on the CIFAR10 dataset. This was implemented through a pytorch and many of the fuctions developed here were used in future projects and [better formalised here](https://github.com/Boyne272/tools).

By Richard Boyne (Github: Boyne272 - CID: 01057503)

19<sup>th</sup> May 2019

Data Source https://www.cs.toronto.edu/~kriz/cifar.html accessed via pytorch



## Repository Structure

- corsework_brief.ipynb is the document we were given describing the task (un-edited)
- ACSE8_CW3.ipynb has all the tasks completed, annotated and has been re-run to ensure no bugs
- CIFAR10_classifier.pth is a pickeled model object (the whole object, not just its parameters) of the LeNet5 model trained on the entire CIFAR10 training data set with a test accuracy of 64.7%
- CIFAR10_classifier_better.pth is the same model as the above trained for fewer epochs so as to reduce overfitting, leading to a higher test accuracy of 65.5%.
