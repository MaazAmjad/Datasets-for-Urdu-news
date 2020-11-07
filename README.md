                                Urdu Fake News Dataset
                              ===========================

                                
    Maaz Amjad, Grigori Sidorov, Alisa Zhila, Helena Gómez-Adorno, Ilia Voronkov, Alexander Gelbukh
                       Natural Language and Text Processing Laboratory
                       Center for Computing Research (CIC)
                       Instituto Politécnico Nacional (IPN)
                       Ciudad de México (Mexico City), Mexico  
---
## CONTENTS
 1. Introduction
 2. Data Annotation
 3. Feedback
 4. Citation Info
 5. Acknowledgments
---

## 1. Introduction

This README demonstrates Urdu fake news datasets that contain news of 5 different news domains. These domains are Sports, Health, Technology, Entertainment, and Business. The real news are collected by combining manual approaches. However, the fake news are collected by crowdsourced annotation (we took the services of the professional journalists).

---

## 2. Data collection

**"Bend the Truth"** dataset contains news in six different domains: technology, education, business, sports, politics, and entertainment. The real news included in the dataset were collected from a variety of mainstream news websites predominantly in Pakistan, India, UK, and the USA. These news channels are BBC Urdu News, CNN Urdu, Express-News, Jung News, Noway Waqat, and many other reliable news websites. The fake news included in this dataset consist of fake versions of the real news in the dataset, written by professional journalists. More details on the data collection are provided in the paper. 

---

## 3. Dataset structure of "Bend the Truth"

This dataset has two folders. Each folder contains real and fake news. There are 5 types of news in this dataset such as technology, business, sports, health, and entertainment. The file names show the category of news. For example, the news categories are sports (sp), technology (tech), etc.

The class distribution for the fake and real news for each dataset is shown below:

| Dataset        | Class | Entries |
|:---------------|:-----:|--------:|
|                | Fake  | 400     |
| Bend the Truth |-------|---------|
|                | Real  | 500     |

---

## 4. Feedback
If you want to know how this dataset was build (include the explanation of crawling and annotation technique) and how we did our experiments for Fake News detection in Urdu language using this dataset, you can read our paper in here: DOI 10.3233/JIFS-179905

*For further questions or inquiries about this dataset, you can contact Maaz Amjad (maazamjad@phystech.edu)* 

---

## 5. Citation Info
This dataset and the other resource can be used for free, but if you want to publish a paper/publication using this dataset, please cite this publication:
```
@article{MaazUrdufake2020,
author = { Maaz Amjad, Grigori Sidorov, Alisa Zhila, Helena G\’{o}mez-Adorno, Ilia Voronkov, Alexander Gelbukh},
title = {Bend the Truth: A Benchmark Dataset for Fake News Detection in Urdu and Its Evaluation},
journal={Journal of Intelligent \& Fuzzy Systems},
volume={39},
number={2},
pages={2457-2469},
year={2020},
publisher={IOS Press}
}
```
---
