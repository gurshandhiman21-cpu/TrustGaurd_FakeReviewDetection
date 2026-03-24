# TrustGuard Fake Review Detection System

## Overview
This project detects fake reviews using NLP and Machine Learning.

Instead of binary classification, it assigns a TrustScore (0–100) to measure authenticity.

## Problem
Fake reviews mislead customers and damage trust in e-commerce platforms.

## Solution
We built a system that:
- Analyzes review text
- Detects promotional patterns
- Calculates a TrustScore
- Classifies review as Fake or Genuine

## Features
- Text preprocessing
- Sentiment analysis (TextBlob)
- TF-IDF vectorization
- Random Forest model
- TrustScore scoring system

## Tech Stack
- Python
- Scikit-learn
- TextBlob
- Kaggle Notebook (Jupyter environment)

## How to Run
1. Download notebook
2. Open in Jupyter/Kaggle
3. Upload dataset
4. Run all cells
5. Test using `check_review()`

## Example Output
Review: "Amazing product must buy"
TrustScore: 33
Likely Fake Review

## Innovation
- TrustScore instead of binary output
- Explainable detection system
