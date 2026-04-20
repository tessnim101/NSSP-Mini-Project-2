# NSSP-Mini-Project-2

This repository contains a series of Jupyter notebooks implementing a  workflow for electromyography (EMG) signal processing, feature extraction and cross-subject analysis.

---

## Contents

### 1. Part1.ipynb - Data Loading & Feature Extraction
- Loads EMG data from `.mat` files
- Preprocesses signals (rectification, smoothing)
- Segments data by stimulus and repetition
- Extracts fundamental EMG features
- Provides exploratory visualizations

### 2. Part2.ipynb - Cross-Subject Analysis
- Processes data from multiple subjects
- Extracts extended feature set:
  - MAV, STD, MAXAV, RMS, WL, SSC
- Evaluates feature consistency across subjects
- Performs statistical analysis:
  - Spearman correlation
  - Coefficient of variation
  - Kruskal-Wallis test
- Visualizes inter-subject variability

### 3. Part3.ipynb - Visualization & Dataset Preparation
- Visualizes EMG and glove (joint angle) data
- Performs frequency analysis (Welch’s method)
- Implements repetition-based data splitting:
  - Train / Validation / Test
- Applies sliding window segmentation:
  - 128 ms window, 50 ms step

---

## Requirements

- Python 3.x
- Jupyter Notebook or JupyterLab

### Dependencies
- numpy
- pandas
- matplotlib
- seaborn
- scipy
- scikit-learn
