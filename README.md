# Vietnamese-Text-classification-with-multilabel using KNN, SVM, Naive Bayes

Input: a text
Output: a Label (include ten Label)




## Report
|Full name|Role|
|:--:|:--:|
| Nguyen Hoang Long| Leader |
| Tran Duc Long| Member |

## Table of contents
1. [Introduction](#1-introduction)
2. [Dataset](#2-Dataset)
3. [Results](#5-results)
4. [References](#6-references)

## 1. Introduction
Throughout this work, there are many approach and we choose SVM, KNN, Bayes to compare the work performance. Firstly, we need to preprocessing data contain word segmentation, because we do this work with Vietnamese text so we don't need to bring that word to original. After preprocessing build SVM, KNN, Bayes Naive model to predict the labels.


## 2. Dataset
This Dataset we collected from https://github.com/duyvuleo/VNTC/tree/master/Data

about the Dataset
  Sự Phân bố Data trong tập Train
<div align='center'>
  <img width="1440" alt="Dataset for train" src = "./images/train_Data">
</div>

 Sự Phân bố Data trong tập Test
<div align='center'>
 <img width ="1440" alt="Dataset for test" src = "https://user-images.githubusercontent.com/350081346_590272103168458_7814506249044237022_n.png">
</div>

## 3. Results
  Confustion maxtrix - Naive Bayes
<div align='center'>
  <img width="1440" alt="Naive Bayes" src = "https://user-images.githubusercontent.com/350121621_3450544831880237_7033670595741997097_n.png">
</div>

  Confustion maxtrix - KNN
<div align='center'>
  <img width ="1440" alt="KNN" src = "https://user-images.githubusercontent.com/350095288_277181891442017_5369898222638496184_n.png">
</div>

  Confustion maxtrix - SVM
<div align='center'>
  <img width ="1440" alt = "SVM" src ="https://user-images.githubusercontent.com/350090809_943613673628366_8404256624121486071_n.png">
</div>
  


## 4. References
Our work is inspired from:
[vietnamese-text-classification
](https://github.com/linhnvc/vietnamese-text-classification.git)
