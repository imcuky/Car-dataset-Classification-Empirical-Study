# Classification Empirical Study 📊
## Naïve Bayes vs Logistic Regression

Welcome to the Classification Empirical Study repository! 🚀 In this project, we compare the performance of Naïve Bayes and Logistic Regression models on the Car Evaluation dataset, which is a multi-class classification task. Let's dive into the details:

### Dataset Overview 🚗
- **Dataset:** [Car Evaluation Dataset](https://archive.ics.uci.edu/dataset/19/car+evaluation)
- **Number of Samples:** 1728
- **Number of Attributes:** 6
- **Number of Classes:** 4 (Unacceptable, Acceptable, Good, Very Good)

### Project Overview 📚
1. **Familiarize with the Task and Dataset**
   - **Goal:** Understand the classification task and dataset characteristics.
   - **Dataset Details:** Explore the number of training examples, features, missing data, etc.

2. **Brainstorm about Attributes (Feature Engineering)**
   - **Features:** Consider the usefulness of features, and identify missing or irrelevant ones.
   - **Feature Exploration:** Examine attribute ranges and visualize them. Discuss the potential benefits of attribute normalization.

3. **Encode the Features**
   - **Logistic Regression:**
     - Expectation: Continuous attributes. Utilize one-hot encoding for discrete attributes.
   - **Naïve Bayes:**
     - Option: CategoricalNB based on the data distribution.

4. **Define 2 Models Using Default Parameters**
   - **Logistic Regression Model:** Understand some parameters;
   - **Naïve Bayes Model:** Explore relevant parameters for Naïve Bayes.

5. **Train/Test/Evaluate Your Models in Cross-Validation**
   - **Cross-Validation:** Employ 4-fold cross-validation.
   - **Evaluation:** Use precision/recall measures. Compare micro and macro averages. Consider class balance impact.

6. **Modify Parameters and Reevaluate**
   - **Experiment 1:**
     - Modify parameters for both models (clearly stated in comments).
   - **Experiment 2:**
     - Further parameter modifications for in-depth analysis.

7. **Analyze Obtained Results**
   - **Quantitative Comparison:** Evaluate all 6 results with the same cross-validation technique.
   - **Micro/Macro Averages:** Discuss differences in precision/recall averages.


Feel free to explore the detailed notebooks in the 'notebooks' directory for a step-by-step journey through the project.

### Catherine Lee, Fall 2023 🍂


[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
