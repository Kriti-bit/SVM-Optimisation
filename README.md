# SVM Parameter Optimisation

#### Kriti Singhal

#### 102017079

## Introduction

Paramater Optimisation for Support Vector Machine(SVM) is a technique to find the best parameters for the SVM model. The parameters that are to be optimised are nu, epsilon and kernel. 10 samples of the available dataset were created using Simple Random Sampling and each sample was then trained and tested using SVM. The dataset used for this project is the Letter Recognition Data Set from the UCI repository. The dataset consists of 20,000 records and the objective is to identify each of a large number of black-and-white rectangular pixel displays as one of the 26 capital letters in the English alphabet. The character images were based on 20 different fonts and each letter within these 20 fonts was randomly distorted to produce a file of 20,000 unique stimuli. Each stimulus was converted into 16 primitive numerical attributes (statistical moments and edge counts) which were then scaled to fit into a range of integer values from 0 through 15.

## Dataset Description

The dataset "Letter Recognition Data Set" has been chosen from the UCI repository and it consists of 20,000 records.
The objective is to identify each of a large number of black-and-white rectangular pixel displays as one of the 26 capital letters in the English alphabet. The character images were based on 20 different fonts and each letter within these 20 fonts was randomly distorted to produce a file of 20,000 unique stimuli. Each stimulus was converted into 16 primitive numerical attributes (statistical moments and edge counts) which were then scaled to fit into a range of integer values from 0 through 15.

<br>

![Data Distribution](/static/distribution.png)

<br>

## Methodology

<br>

![Flowchart](/static/flowchart.jpg)

<br>

## Results

The convergence graph for the best sample was plotted for all accuracies obtained over the 1000 iterations. The graph is shown below.

<br>

![graph](static\convergence_graph2.png)

<br>
