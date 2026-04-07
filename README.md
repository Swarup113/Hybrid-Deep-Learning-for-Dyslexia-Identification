# Multimodal Dyslexia Detection using Machine Learning and Deep Learning

---

## Overview
Dyslexia is a neurological condition that affects reading, writing, and spelling abilities due to difficulties in processing written language. Affecting over 10% of the global population, early detection is essential for timely intervention.

This repository presents a multimodal framework for dyslexia detection using Electroencephalography (EEG), Eye Tracking (ET), and Handwriting Text Images (HTI). The study evaluates both Machine Learning (ML) and Deep Learning (DL) approaches and proposes a hybrid CNN-BiLSTM model for improved performance and generalizability.

## DOI:
https://doi.org/10.1109/ICCCNT61001.2024.10724337

---

## Research Objectives

| Objective ID | Description |
|--------------|------------|
| O1 | Detect dyslexia using multimodal data |
| O2 | Compare ML and DL approaches |
| O3 | Evaluate modality-wise performance |
| O4 | Develop a hybrid DL model for improved accuracy |

---

## Data Modalities

| Modality | Description | Data Type |
|----------|------------|----------|
| EEG | Brain signal activity | Time-series |
| Eye Tracking (ET) | Eye movement patterns during reading | Sequential |
| Handwriting Text Images (HTI) | Handwritten text samples | Image |

---

## Model Architecture Comparison

| Category | Model | Description |
|----------|------|------------|
| DL | CNN | Extracts spatial features from images |
| DL | BiLSTM | Captures sequential dependencies in data |
| DL | CNN-BiLSTM | Hybrid model combining spatial and temporal learning |
| ML | Traditional Models | Baseline classifiers for comparison |

---

## Methodology Pipeline

| Step | Process | Description |
|------|--------|------------|
| 1 | Data Acquisition | EEG, ET, and HTI datasets |
| 2 | Preprocessing | Noise removal and data cleaning |
| 3 | Feature Extraction | Modality-specific feature engineering |
| 4 | Data Splitting | Training and testing partition |
| 5 | Model Training | ML and DL model training |
| 6 | Hyperparameter Tuning | Optimization of model parameters |
| 7 | Evaluation | Performance analysis using metrics |

---

## Evaluation Metrics

| Metric | Purpose |
|--------|--------|
| ROC Curve | Measures classification performance |
| Confusion Matrix | Evaluates prediction distribution |
| Accuracy | Overall prediction correctness |
| Loss Curve | Training and validation convergence |

---

## Validation Techniques

| Technique | Description |
|----------|------------|
| K-Fold Cross Validation | Multi-fold robustness validation |
| Hyperparameter Tuning | Optimization of learning parameters |
| Optimizer Comparison | Evaluation of different optimizers |

---

## Results

| Modality | Accuracy |
|----------|----------|
| EEG | 96.57% |
| Eye Tracking (ET) | 97.62% |
| Handwriting Text Images (HTI) | 95.81% |

---

## Model Performance Summary

| Aspect | Observation |
|--------|------------|
| Best Model | CNN-BiLSTM |
| Performance | High accuracy across all modalities |
| Generalization | Strong across multimodal inputs |
| Stability | Consistent across validation techniques |

---

## Comparative Analysis

| Technique | Outcome |
|----------|--------|
| Traditional ML Models | Lower performance |
| Standalone DL Models | Moderate performance |
| Late Fusion Techniques | Improved but inconsistent |
| Ensemble Learning | Competitive but less stable |
| Proposed CNN-BiLSTM | Best and most consistent performance |

---

## Key Contributions

- Multimodal dyslexia detection using EEG, ET, and HTI data  
- Hybrid CNN-BiLSTM architecture for improved classification  
- Comparative analysis of ML, DL, fusion, and ensemble methods  
- Strong generalization validated through cross-validation  

---

## Project Structure

| Directory/File | Description |
|---------------|------------|
| data/ | Multimodal datasets (EEG, ET, HTI) |
| preprocessing/ | Data cleaning and preprocessing scripts |
| models/ | Model architectures and trained weights |
| experiments/ | Training and evaluation scripts |
| results/ | Performance metrics and visualizations |
| README.md | Project documentation |

---

## Ethical Considerations

| Concern | Description |
|--------|------------|
| Data Privacy | Sensitive cognitive data must be protected |
| Bias | Model may vary across demographics |
| Clinical Use | Not intended for medical diagnosis |

---

## Disclaimer
This project is intended strictly for research and academic purposes. It is not a substitute for professional diagnosis or clinical assessment.

---

## Keywords

| Domain | Terms |
|-------|------|
| Application | Dyslexia Detection, Learning Disability Prediction |
| Data | EEG, Eye Tracking, Handwriting Images |
| Techniques | Deep Learning, Machine Learning |
| Model | CNN-BiLSTM, Multimodal Learning |

---

## Citations

@INPROCEEDINGS{10724337,
  author={Dewanjee, Swarup and Muntaha, Sidratul},
  booktitle={2024 15th International Conference on Computing Communication and Networking Technologies (ICCCNT)}, 
  title={Hybrid Deep Learning for Dyslexia Identification through Heterogeneous Cognitive and Behavioral Data Analysis}, 
  year={2024},
  volume={},
  number={},
  pages={1-7},
  keywords={Deep learning;Accuracy;Computational modeling;Writing;Brain modeling;Dyslexia;Feature extraction;Electroencephalography;Data models;Ensemble learning;Learning Disability Prediction;Dyslexia Detection;Hybrid Deep Learning;Multi-Modal;EEG;Eye Tracking;Handwriting Image},
  doi={10.1109/ICCCNT61001.2024.10724337}}
