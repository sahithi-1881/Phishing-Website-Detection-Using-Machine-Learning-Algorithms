# Phishing-Website-Detection-Using-Machine-Learning-Algorithms

## Overview
Phishing is a significant cyber threat involving the creation of fake websites to deceive users into sharing sensitive information. This project addresses the issue by leveraging machine learning techniques to accurately detect phishing websites.
Using datasets from trusted sources like PhishTank and the University of New Brunswick, we developed a system that achieved 94% accuracy in detecting phishing websites, using XGBoost algorithm.

## Features
1. **AI-Powered Detection**: Utilizes machine learning algorithms like XGBoost, Random Forest, Decision Tree, and SVM.
2. **Comprehensive Feature Extraction**: Extracts critical features from URLs, such as:
     Address bar, domain, and HTML/JavaScript-based characteristics.
3. **High Accuracy**: XGBoost outperformed other models, achieving a detection accuracy of 94%.
4. **Efficient Workflow**: Processes over 10,000 URLs to detect phishing websites in real-time.

## System Architecture
The system follows these key steps:
1.**Data Collection**: URLs sourced from PhishTank and UNB datasets.
2.**Feature Extraction**: Features like URL length, IP presence, and redirection behaviors are analyzed.
3.**Model Training**: Supervised learning models trained on an 80-20 split of data.
4.**Performance Evaluation**: Models evaluated using metrics like accuracy, precision, and recall.

## Methodology
**1.Dataset Preparation**:
Legitimate URLs: Sourced from UNB datasets.
Phishing URLs: Sourced from PhishTank.
Data split: 8,000 training and 2,000 testing samples.

**2.Feature Engineering**:
Address-based: URL length, presence of '@', redirection using "//".
Domain-based: DNS record, domain age, web traffic metrics.
HTML/JavaScript-based: iFrame redirection, right-click disablement.

**3.Machine Learning Models**:
Support Vector Machines (SVM)
Decision Tree
Random Forest
XGBoost (Best performer with 94% accuracy)

**4.Evaluation Metrics**:
Confusion Matrix
Accuracy, Precision, Recall, and F1-Score.
