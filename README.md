                                Urdu Fake News Dataset
                              ===========================

                                August 1st October, 2019
                                
    Maaz Amjad, Grigori Sidorov, Alisa Zhila, Helena Gómez-Adorno, Alexander Gelbukh, Ilia Voronkov

                       Natural Language and Text Processing Laboratory
                       Center for Computing Research (CIC)
                       Instituto Politécnico Nacional (IPN)
                       Ciudad de México (Mexico City), Mexico  

## CONTENTS
 1. Introduction
 2. Data Annotation
 3. Feedback
 4. Citation Info
 5. Acknowledgments

## 1. Introduction

This README demonstrates Urud fake news datasets which contain news of 5 different news domains. These domains are Sports, Health, TEchnology, Entertainment and Business. The real news are coolected by combining manual approaches. However, the fake news are collected by crowdsourced annotation (we took the services of the professional journalists)


## 2. Data collection

"The Bend the Truth" dataset contains news in six different domains: technology, education, business, sports, politics, and entertainment. The real news included in the dataset were collected from a variety of mainstream news websites predominantly in the Pakistan, India, UK and USA. These news channels are BBC Urdu News, CNN Urdu, Express News, Jung News, Naway Waqat and many others reliable news websites. The fake news included in this dataset consist of fake versions of the real news in the dataset, written by professional journalists. More details on the data collection are provided in the paper. 


## 3. Dataset structure of "Bend the Truth"

This dataset has two folders. Each folder contains real and fake news. There are 5 types of news in this dataset such as technology, business, sports, health and entertainment. The file names shoes the catagory of news. For example, the news catogary sports (sp), technology (tech) etc.

The class distributio for the fake and real news for each dataset is shown below:

| Dataset        | Class | Entries |
|----------------|-------|---------|
|                | Fake  | 400     |
| Bend the Truth |-------|---------|
|                | Real  | 500     |


## 3. Feedback
If you want to know how this dataset was build (include the explanation of crawling and annotation technique) and how we did our experiments for Fake News detection in Urdu language using this dataset, you can read our paper in here:

*For further questions or inquiries about this dataset, you can contact Maaz Amjad (maazamjad@phystech.edu)* 

## 4. Citation Info
This dataset and the other resource can be used for free, but if you want to publish paper/publication using this dataset, please cite this publication:

@article{Maaz-Urdufake,
author = { Maaz Amjad, Grigori Sidorov, Alisa Zhila, Helena G\’{o}mez-Adorno, Alexander Gelbukh, Ilia Voronkov},
title = {Bend the Truth: A Benchmark Dataset for Fake News Detection in Urdu and Its Evaluation},
journal = {Journal of Intelligent and Fuzzy Systems},
year = {2019}
}

## 5. Acknowledgments
The work was done with partial support of CONACYT project 240844 and SIP-IPN projects 20195719.



