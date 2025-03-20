# Text-Based Emotion Recognition in Tamil (Label Correction using Clustering)

This repository contains code and methodology for correcting mislabeled data in a text-based emotion recognition dataset in Tamil language using clustering techniques. The dataset contains sentences labeled with six common emotions: **sad, anger, surprise, disgust, happy, and fear**.

## Introduction

The aim of this research is to improve the quality of emotion-labeled datasets by identifying and correcting mislabeled data using clustering techniques. This approach is particularly applied to text-based emotion recognition in the Tamil language.

## Dataset Description

The dataset consists of sentences labeled with the following six emotions:

- Sad
- Anger
- Surprise
- Disgust
- Happy
- Fear

## Methodology

1. **Tokenization and Vectorization:**

   - The sentences are tokenized and converted to vector representations for clustering.

2. **Clustering:**

   - The data is divided into 6 clusters using an unsupervised clustering technique.
   - For each cluster, the most common label is identified and assigned as the predominant emotion of that cluster.
   - Labels are corrected based on this clustering approach.

3. **Issue Faced:**
   - The clustering process reduced the original six emotions to four, indicating loss of emotional distinction.
4. **Future Work:**
   - Exploring alternative methodologies to improve label correction without reducing the number of emotions.

## Usage

Clone the repository:

```bash
git clone https://github.com/sankavimohan/Text-Based-Emotion-Recognition-in-Tamil-Language.git
```
