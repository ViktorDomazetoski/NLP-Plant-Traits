# Using Natural Language Processing to Extract Plant Functional Traits from Unstructured Text
This repository contains the codebase used in the dataset creation, model training and evaluation, and as such can be used to recreate the results in study.

## Overview
 We propose a natural language processing (NLP) pipeline that automatically extracts trait information from an unstructured textual description of a species and provides a confidence score. To achieve this, we employ a textual classification model for categorical traits and a question answering model for numerical traits. We demonstrate the proposed pipeline on five categorical traits (growth form, life cycle, epiphytism, climbing habit and life form), and three numerical traits (plant height, leaf length, and leaf width). We evaluate the performance of our new NLP pipeline by comparing results obtained using different alternative modeling approaches ranging from a simple keyword search to advanced deep learning models, on two extensive databases, each containing more than 50,000 species’ descriptions.

## Installation

## Usage 
The codebase consists of jupyter notebooks divided by chapters:
* 01\. - contain the code used to preprocess the original descriptions
* 02.x - allow the creation of the databased by combining species' description data and species' functional trait data
* 03.x - used to train and evaluate the simpler classification models: an approach based on regular expressions and a logistic regression model based on bag of words 
* 04.x - used to train and evaluate the deep learning transformer classification models
* 05\. - used to evaluate the deep learning transformer question answering models  
* 06.x - result visualization
* 07.x - sample usage 
 
## Authors
- [Viktor Domazetoski](https://github.com/ViktorDomazetoski)
- Holger Kreft
- Helena Bestova
- Philipp Wieder
- Radoslav Koynov
- Alireza Zarai
- [Patrick Weigelt](https://github.com/patrickweigelt)
