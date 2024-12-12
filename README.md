# Banana Quality Prediction using Machine Learning

This repository contains the implementation of a machine learning model designed to predict banana quality based on measurable attributes. The model leverages a Random Forest Classifier to classify bananas as high-quality or low-quality.

## Features

The dataset used for the model includes the following features:
- *Sweetness*: Sugar concentration.
- *Weight*: Physical weight of the banana.
- *Harvest Time*: Time since harvesting.
- *Size*: Dimensions of the banana.
- *Softness*: Textural ripeness indicator.
- *Ripeness*: A qualitative measure of ripeness on a scale.
- *Acidity*: Indicator of tartness.

The target variable is binary, categorizing bananas as either high-quality or low-quality.

## Model Overview

### Key Highlights
- *Model Used*: Random Forest Classifier.
- *Evaluation Metrics*: 
  - Accuracy
  - Confusion Matrix
  - Feature Importance
  - Precision, Recall, and F1-Score

### Performance
The model achieved an accuracy of 98%, with high precision and recall values, demonstrating excellent predictive capabilities.

## Results and Insights

1. *Feature Importance*:
   - Sweetness and Weight were identified as the most critical features for determining banana quality.
   - Acidity was the least influential feature.

2. *Confusion Matrix Analysis*:
   - True Positives: 801
   - True Negatives: 759
   - False Positives: 22
   - False Negatives: 18

3. *Implications*:
   - Improved operational efficiency by reducing waste.
   - Economic benefits through accurate classification.
   - Enhanced consumer satisfaction.

## Installation

Clone the repository:

```bash
git clone <repository-link>
