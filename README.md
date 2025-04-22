# Predicting Concrete Compressive Strength and Classification

Concrete plays a vital role in civil engineering, and its compressive strength is determined by a complex, nonlinear relationship with variables like age and ingredient composition. This project focuses on creating machine learning models to predict the **Concrete Compressive Strength** and to classify the **ConcreteClass** based on various concrete formulations.

## Data Source
The dataset used in this project is sourced from the [**UCI Machine Learning Repository**](https://archive.ics.uci.edu/ml/datasets/Concrete+Compressive+Strength), originally from I-Cheng Yeh's research: 
> "Modeling of strength of high performance concrete using artificial neural networks,"  
> Cement and Concrete Research, Vol. 28, No. 12, pp. 1797-1808 (1998).

---

## Problem 1: Regression - Predicting Concrete Compressive Strength

### Objective
Develop a machine learning model to predict the **Concrete Compressive Strength** given the quantities of input ingredients and the number of days (Age) for curing the concrete.

### Steps
1. **Data Preparation**: Ensure the data is properly formatted for scikit-learn.
2. **Feature Selection**: Identify and separate features (X) and target (y).
3. **Baseline Model**: Establish a base score for the model to measure progress.
4. **Data Validation**: Validate the data to ensure sufficient samples for both training and testing.
5. **Modeling**: Use at least **7 conventional machine learning algorithms** and **Deep Learning** (Tensorflow - Keras or Pytorch) to predict **Concrete Compressive Strength**.

---

## Problem 2: Classification - Predicting ConcreteClass

### Objective
Develop a machine learning model to classify the **ConcreteClass** for a given concrete recipe.

### Data Transformation
- Create new categorical targets based on numeric data.
- Convert the **Plasticizer** feature to text.
- Remove the **Strength** feature and replace it with the **ConcreteClass** categorical target.

### Steps
1. **Data Preparation**: Ensure the data is properly formatted for scikit-learn.
2. **Feature Selection**: Identify and separate features (X) and target (y).
3. **Baseline Model**: Establish a base score for the model to measure progress.
4. **Data Validation**: Validate the data to ensure sufficient samples for both training and testing.
5. **Modeling**: Use at least **7 conventional machine learning algorithms** and **Deep Learning** (Tensorflow - Keras or Pytorch) to predict **ConcreteClass**.
