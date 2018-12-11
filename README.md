
# Introduction

## Introduction
This lesson summarizes the topics we'll be covering in section 30 and why they'll be important to you as a data scientist.

## Objectives
You will be able to:
* Understand and explain what is covered in this section
* Understand and explain why the section will help you to become a data scientist

## Logistic Regression In-depth: MLE and Gradient descent

In the last section we introduced logistic regression as a binary classifier and looked at various techniques for evaluating model fit for classifiers. In this section, we're going to go deeper into logistic regression to help you to deepen your intuition and understandings of some key concepts in data science.

We start off by reviewing the concept of Maximum Likelihood Estimation. We then look at how logiastic regression can be viewed through the lens of MLE.

From there we review the idea of a gradient descent for numerically approximating an optimal solution for a problem (we'd used it previously to calculate parameters for a linear regression). And then we give you some experience building a gradient descent algorithm from scratch for a linear regression.

With that background, we then ask you to build a logistic regression from scratch, stepping you through the process of creating a linear regression, applying a sigmoid function and then performing a gradient descent to find the minima of the cost function.

We then round out the section by asking you to make probability predictions, create an ROC curve, and generate a confusion matrix - both for your hand coded model and foot the built-in method in scikit-learn.

Finally we ask you to alter the regularization parameter in scikit-learn to see how that affects the Area Under the Curve (AUC).



## Summary

In this section, we return to the concepts of MLE and Gradient Descent, giving you experience in hand coding the formulae to build the comfort and experience to be able to take math from a paper and develop a solution in Python. The practice should also deepen your comfort and familiarity when thinking about MLE and gradient descent in the future.

