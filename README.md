# Malicious URL Classification with Machine Learning
<img src="https://github.com/sajan-sarker/Malicious_URL_Classification/blob/main/results/img.png?raw=true" alt="Learning Curve" width="1000"/>

## Overview
This project implements a machine learning-based classifier to classify malicious URLs, categorize them into types such as benign, phishing, defacement, and malware. 

## Dataset
#### [Kaggle Malicious URLs Dataset](https://www.kaggle.com/datasets/sid321axn/malicious-urls-dataset) 

#### Sample Dataset

<table>
  <thead>
    <tr> 
      <th>URL</th>
      <th>Type</th>
    </tr>
  </thead>
  <tbody>
    <tr>
      <td>br-icloud.com.br</td>
      <td>phishing</td>
    </tr>
    <tr>
      <td>mp3raid.com/music/krizz_kaliko.html</td>
      <td>benign</td>
    </tr>
    <tr>
      <td>bopsecrets.org/rexroth/cr/1.htm</td>
      <td>benign</td>
    </tr>
    <tr>
      <td>http&#58;//www&#46;vnic.co/khach-hang.html</td>
      <td>defacement</td>
    </tr>
  </tbody>
</table>


#### Dataset Class Distribution 
<img src="https://github.com/sajan-sarker/Malicious_URL_Classification/blob/main/results/multi_class_distribution.png?raw=true" alt="Learning Curve" width="500"/>

## Features
**Feature Extraction**: Uses tldextract and urlparse to extract features like domain, path, and URL characteristics. \
**Data Analysis**: Analyze the URLs and extracted features. \
**Model Training**: Train multiple classifiers including: Decision Tree, Random Forest, XGBoost, CatBoost, KNN, Voting Classifier and perform hyperparameter tuning. \
**Evaluation**: Findout models Accuracy, Precision, Recall, F1-score, ROC-AUC, PR Curve and confusion Matrix. \
**Prediction**: Provides functionality to redict the type of a new URL with confidence scores. 

## Results:
<img src="https://github.com/sajan-sarker/Malicious_URL_Classification/blob/main/results/model_performances.png?raw=true" alt="Model Performances" width="800"/>
<img src="https://github.com/sajan-sarker/Malicious_URL_Classification/blob/main/results/roc_auc_scores.png?raw=true" alt="Model ROC-AUC Scores" width="800"/>
