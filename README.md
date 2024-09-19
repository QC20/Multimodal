# Investigating Persuasive Communication with Multi-modal ML
Multimodal Research in Automatic Persuasion Recognition


This repository presents a multi-modal approach to investigating, analyzing, and interpreting persuasive communication using machine learning techniques.

## Introduction
In this paper, we explore the persuasive Opinion Multimedia (POM) dataset and propose a hypothesis based on critical features. We hypothesize that:

1. Speaker persuasion can be predicted using text and audio features by employing supervised machine learning methods.
2. Bi-modal classification yields higher prediction accuracy compared to uni-modal classification for the specific modalities of text and audio.

## Methodology
Our approach involves collating (fusing) the text and audio modalities to create a bi-modal dataset. We then apply a Random Forest Classifier to predict speaker persuasion. We evaluate the accuracy of our model and consider the implications of the research design on the generalizability of the results.

## Results
By combining the text and audio modalities, we achieve an accuracy score of 71.68% using the bi-modal Random Forest Classifier. However, it is important to note the limitations and considerations associated with the chosen research design and its impact on the generalizability of the presented results.

## Repository Structure
- `data/`: This directory contains the POM dataset used for analysis.
- `code/`: This directory contains the Python scripts used for data preprocessing, model training, and evaluation.
- `models/`: This directory contains the trained models saved in the appropriate format.
- `results/`: This directory contains the evaluation results and performance metrics of the models.

## Getting Started
1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/persuasive-communication-analysis.git
