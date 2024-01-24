## Table of Contents
1. [Overview](#overview)
   - [1. Install Libraries](#1-install-libraries)
   - [2. Import Libraries](#2-import-libraries)
   - [3. Load Data](#3-load-data)
   - [4. Multiclass Specificity Score](#4-multiclass-specificity-score)
   - [5. Objective Function](#5-objective-function)
   - [6. Binary Grey Wolf Optimizer (BGWO)](#6-binary-grey-wolf-optimizer-bgwo)
   - [7. Initialize Population](#7-initialize-population)
   - [8. Execution Script](#8-execution-script)
2. [Install Libraries](#1-install-libraries)
   - Execute these commands in the terminal to install essential libraries—numpy, pandas, and scikit-learn.
3. [Import Libraries](#2-import-libraries)
   - Import statements are used to bring in necessary Python libraries for data manipulation, machine learning, and performance metric evaluation.
4. [Load Data](#3-load-data)
   - The data loading step involves reading an artificial EEG dataset from a CSV file and extracting features (X) and labels (y) for subsequent analysis.
5. [Multiclass Specificity Score](#4-multiclass-specificity-score)
   - In this section, a function is defined to calculate the specificity score for multiclass classification tasks using a confusion matrix.
6. [Objective Function](#5-objective-function)
   - The objective function is pivotal for BGWO-SVM. It evaluates the performance of selected EEG channels based on accuracy, F1-score, recall, and specificity, with the aim of minimizing their negative combination.
7. [Binary Grey Wolf Optimizer (BGWO)](#6-binary-grey-wolf-optimizer-bgwo)
   - This section outlines the BGWO algorithm, providing an explanation of its steps to optimize the selection of EEG channels based on the defined objective function.
8. [Initialize Population](#7-initialize-population)
   - The initialization function creates a random population of binary values, representing the activation or deactivation of EEG channels.
9. [Execution Script](#8-execution-script)
   - The main script sets parameters, loads artificial EEG data, initializes the SVM classifier, runs the BGWO optimizer, and prints the results—specifically, the selected channels and their corresponding performance.
