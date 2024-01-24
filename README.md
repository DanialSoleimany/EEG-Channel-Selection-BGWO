1. **Project Title**
   - **Enhancing Person Identification through EEG Channel Selection using Binary Grey Wolf Optimization Algorithm**

2. **Project Description**
   - This project implements a Binary Grey Wolf Optimizer (BGWO) to intelligently select optimal channels in an Electroencephalogram (EEG) dataset for effective person identification. The artificial EEG dataset is loaded from a CSV file, and the objective function combines key performance metrics such as accuracy, F1-score, recall, and specificity. The BGWO algorithm optimizes the selection of EEG channels by minimizing the negative combination of these metrics. Employing a support vector machine (SVM) classifier with a radial basis function (RBF) kernel enhances the accuracy of person identification. The primary goal of the project is to efficiently identify the most relevant EEG channels, ensuring a high level of classification performance.

3. **Table of Contents**
   - [Project Title](#project-title)
   - [Project Description](#project-description)
   - [Table of Contents](#table-of-contents)
   - [Install Libraries](#install-libraries)

4. **Install Libraries**
   - Ensure you have the necessary libraries installed by running the following commands:
     ```bash
     pip install numpy
     pip install pandas
     pip install scikit-learn
     ```
