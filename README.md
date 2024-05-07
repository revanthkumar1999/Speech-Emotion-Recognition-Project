# Speech Emotion Recognition Project

## Project Overview

This repository hosts the Speech Emotion Recognition project, which uses the RAVDESS dataset to develop machine learning models capable of identifying emotions from speech. The project addresses mood, intensity, and pitch fluctuations in speech using advanced feature extraction techniques and algorithms such as SVM, KNN, and Random Forest, targeting applications in mental health, customer service, and human-computer interaction.

## Table of Contents
- [Introduction](#introduction)
- [Contribution to Sustainability](#contribution-to-sustainability)
- [Motivation](#motivation)
- [Technical Architecture](#technical-architecture)
- [Data and Tools](#data-and-tools)
- [Model Development and Evaluation](#model-development-and-evaluation)
- [Deployment and Usage](#deployment-and-usage)
- [Team and Acknowledgment](#team-and-acknowledgment)
- [Team Members](#team-members)
- [Lessons Learned](#lessons-learned)
- [References](#references)

## Introduction

Emotion recognition from speech is a key aspect of artificial intelligence that enhances applications from mental health to security. This project utilizes the RAVDESS Emotional Speech Audio collection, applying machine learning algorithms and preprocessing techniques like SMOTE to achieve a balanced dataset.

## Contribution to Sustainability

The project aligns with the United Nations SDGs, particularly SDG 3 (Good Health and Well-being) and SDG 4 (Quality Education). It contributes to enhanced well-being and educational outcomes by improving mental health diagnostics and creating adaptable learning environments.

## Motivation

Detecting and analyzing emotions from speech is crucial for understanding human sentiments and enhancing interactions with technology. The goal is to develop robust models that accurately classify emotions, reducing biases and misinformation.

## Technical Architecture

- **Data Management:** Automated scripts manage the RAVDESS dataset effectively.
- **Feature Extraction:** Employing techniques such as MFCCs, spectral contrast, and chroma features to capture the nuances of emotional speech.
- **Model Training:** Utilizing SVM, KNN, and Random Forest with hyperparameter tuning to optimize performance.
- **Evaluation and Tuning:** Metrics like accuracy, precision, recall, and F1-score are used to evaluate and select the best models.

## Data and Tools

- **Dataset:** RAVDESS Emotional speech audio, available [here](https://www.kaggle.com/datasets/uwrfkaggler/ravdess-emotional-speech-audio).
- **Tools:** Librosa, Scikit-learn, Joblib, Python, and others that facilitate data analysis, model training, and deployment.

## Model Development and Evaluation

Several models were developed and evaluated, with the Random Forest model outperforming others by achieving the highest accuracy and demonstrating robustness against overfitting.

## Deployment and Usage

The best-performing model (Random Forest) was serialized using Joblib and is prepared for integration into real-time applications for practical emotion recognition.

## Lessons Learned

The project emphasized the importance of data preparation, the impact of data imbalances on model performance, and the effectiveness of API-driven architecture for scalable solutions.

## References

- https://zenodo.org/records/1204914
