**Title:**
- Enhancing Person Identification Accuracy through Optimal EEG Channel Selection using Binary Grey Wolf Algorithm

**Description:**
- This project introduces a novel method to improve person identification accuracy by utilizing the Binary Grey Wolf Optimization (BGWO) algorithm for EEG channel selection. By strategically selecting optimal channels from an Electroencephalogram (EEG) dataset, the project aims to improve the precision of person identification. The process involves loading an artificial EEG dataset from a CSV file and creating a comprehensive objective function that combines essential performance metrics such as accuracy, F1-score, recall, and specificity. The BGWO algorithm is then applied to minimize the negative combination of these metrics, ensuring the selection of the most informative EEG channels. To further enhance accuracy, a Support Vector Machine (SVM) classifier with a radial basis function (RBF) kernel is employed for person identification. The primary goal of the project is to efficiently identify relevant EEG channels, ultimately achieving superior classification performance.

## Table of Contents
1. [Overview](#overview)
   - [Install Libraries](#install-libraries)
   - [Import Libraries](#import-libraries)
   - [Load Data](#load-data)
   - [Multiclass Specificity Score](#multiclass-specificity-score)
   - [Objective Function](#objective-function)
   - [Binary Grey Wolf Optimizer (BGWO)](#binary-grey-wolf-optimizer-bgwo)
   - [Initialize Population](#initialize-population)
   - [Execution Script](#execution-script)

**Install Libraries:**
```bash
pip install numpy
pip install pandas
pip install scikit-learn
```

**Import Libraries:**
- Import statements are used to bring in necessary Python libraries for data manipulation, machine learning, and performance metric evaluation.

**Load Data:**
- The data loading step involves reading an artificial EEG dataset from a CSV file and extracting features (X) and labels (y) for subsequent analysis.

**Multiclass Specificity Score:**
- In this section, a function is defined to calculate the specificity score for multiclass classification tasks using a confusion matrix.

**Objective Function:**
- The objective function is pivotal for BGWO-SVM. It evaluates the performance of selected EEG channels based on accuracy, F1-score, recall, and specificity, with the aim of minimizing their negative combination.

**Binary Grey Wolf Optimizer (BGWO):**
- This section outlines the BGWO algorithm, providing an explanation of its steps to optimize the selection of EEG channels based on the defined objective function.

**Initialize Population:**
- The initialization function creates a random population of binary values, representing the activation or deactivation of EEG channels.

**Execution Script:**
- The main script sets parameters, loads artificial EEG data, initializes the SVM classifier, runs the BGWO optimizer, and prints the results—specifically, the selected channels and their corresponding performance.
