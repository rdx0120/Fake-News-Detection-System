# Fake News Detection

## Overview

This repository contains the code and resources for our project titled **"Advanced Approaches to Combatting Disinformation: A Comprehensive Analysis for Fake News Detection."** The project aims to tackle the proliferation of fake news using various machine learning techniques. By vectorizing news titles and analyzing word tokens, our models classify news articles as either real or fake, contributing to the ongoing efforts to ensure the accuracy and reliability of information in the digital age.

## Table of Contents

- [Introduction](#introduction)
- [Methodology](#methodology)
- [Datasets](#datasets)
- [Algorithms Used](#algorithms-used)
- [Results](#results)
- [How to Run](#how-to-run)
- [References](#references)
- [Contributors](#contributors)

## Introduction

Fake news has emerged as a significant threat, especially in the political domain, where it can influence public opinion and cause societal harm. This project addresses the challenge of detecting fake news by leveraging machine learning models. Our approach combines various algorithms, such as Decision Trees, SVM, and Random Forest, to achieve high accuracy in classification.

## Methodology

Our methodology involves:
1. **Data Collection**: We used multiple datasets from Kaggle that contain both real and fake news articles.
2. **Feature Engineering**: We focused on vectorizing news titles and extracting linguistic features for analysis.
3. **Model Training**: We trained multiple machine learning models, including Naive Bayes, Logistic Regression, Decision Trees, SVM, and Random Forest, to classify news articles.
4. **Evaluation**: We evaluated the models using a confusion matrix and accuracy metrics to determine their effectiveness.

## Datasets

The datasets used in this project are sourced from Kaggle and include news articles from various domains. The datasets (`true.csv` and `fake.csv`) are included in the `Dataset.7z` file. Please extract this file before running the code. These datasets contain labeled examples of real and fake news articles.

## Algorithms Used

- **Naive Bayes**
- **Logistic Regression**
- **Support Vector Machine (SVM)**
- **Decision Tree Learning**
- **Random Forest**

## Results

The performance of our models is as follows:
- **Decision Tree**: 99.65% accuracy
- **Support Vector Machine (SVM)**: 99.57% accuracy
- **Random Forest**: 99.12% accuracy
- **Logistic Regression**: 98.83% accuracy
- **Naive Bayes**: 94.81% accuracy

## How to Run

1. **Clone the Repository**:
   ```bash
   git clone https://github.com/yourusername/FakeNewsDetectionSystem.git
   cd FakeNewsDetectionSystem

2. **Extract the Dataset**: Unzip the `Dataset.7z` file to extract `true.csv` and `fake.csv`:
   ```bash
   unzip Dataset.7z
   ```
   Ensure the `true.csv` and `fake.csv` files are in the same directory as     the `.ipynb` file.
   
3. **Install Dependencies: Make sure you have Python installed. Then, install the required libraries**:
   ```bash
   pip install -r requirements.txt
   ```

4. **Run the Jupyter Notebook**: Open the `CYBR604-Final_Project.ipynb` file in Jupyter Notebook:
   ```bash
   jupyter notebook CYBR604-Final_Project.ipynb
   ```
   
5. **View Results**: The notebook includes step-by-step outputs for the machine learning models and their accuracy metrics.

## References

- [The long and brutal history of fake news](https://www.politico.com/magazine/story/2016/12/fake-news-history-long-violent-214535)
- [Fake News Detection using Deep Learning](https://www.ieee.org)

## Contributors

- **Parshwa Paresh Bhavsar** - [Email](mailto:parshwa2108@tamu.edu)
- **Rohan Dalvi** - [Email](mailto:rohan.dalvi@tamu.edu)
