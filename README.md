# Wine Quality Prediction from Review Text

## Overview
This project is a **deep learning model** that predicts whether a wine is **high quality (90+ points)** or not based solely on its **review text**.  
It uses **natural language processing (NLP)** to analyze wine descriptions and classify them into **high quality** or **not high quality**.

---

## Features
- Predicts if a wine is rated **90+ points** based on text reviews
- Implements **two approaches**:
  1. **Pretrained embeddings** (Google’s NNLM 50-dimensional embeddings via TensorFlow Hub)
  2. **LSTM network** for sequence modeling
- Provides probability scores and binary classification
- Includes training, validation, and testing pipelines
- Generates **accuracy and loss plots** for model evaluation

---

## Dataset
- Uses a **wine reviews dataset** (`wine-reviews.csv`)  
- Relevant columns: `description`, `points`  
- Ratings are converted into a **binary label**:
  - `1` → `points >= 90` (high quality)  
  - `0` → `points < 90` (not high quality)

---

## Installation

1. Clone the repository (or open in Google Colab)
   ```bash
   git clone https://github.com/skeleton111222/Wine-Quality-Prediction-from-Review-Text
3. Install required packages
4. Run it
