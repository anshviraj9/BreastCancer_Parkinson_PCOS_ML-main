# Machine Learning Project - Disease Detection with Genetic Algorithm Optimization

This project focuses on applying a genetic algorithm to optimize machine learning models for detecting a disease:

**Breast Cancer**


## Datasets

The datasets used in this project are sourced from Kaggle:

- [Breast Cancer Wisconsin Data](https://www.kaggle.com/datasets/uciml/breast-cancer-wisconsin-data/): Features extracted from breast mass aspirates.

## Models and Genetic Algorithm Optimization

### 1. Breast Cancer Detection

#### Models Evaluated:

- Logistic Regression
- Random Forest
- AdaBoost  
- Decision Tree
- K-Nearest Neighbors
- Support Vector Machine (Linear)
- Support Vector Machine (RBF)

The genetic algorithm is specifically applied to logistic regression, resulting in an accuracy improvement from 96.5% to 98.6%.


## Genetic Algorithm Workflow

1. **Initialization:** Random population of binary chromosomes indicating selected/not selected features.
2. **Fitness Calculation:** Calculate fitness scores based on model accuracy.
3. **Selection:** Choose the best-scoring chromosomes.
4. **Crossover:** Create a new population through chromosome crossover.
5. **Mutation:** Introduce random mutations in chromosomes.
6. **Repeat:** Iteratively repeat steps 2-5 for multiple generations.

## Results 

Application of the genetic algorithm optimization provides notable improvements:

- Breast Cancer: Logistic Regression accuracy improves from 96.5% to 98.6%

The optimal feature subsets selected by the genetic algorithm are detailed in the notebook.

## Usage

The IPython notebook contains the full code implementation. To use:

1. Install requirements: `numpy`, `pandas`, `scikit-learn`, `matplotlib`  
2. Run Jupyter notebook
3. Run cells in order

The outputs include accuracy scores, confusion matrices, and feature importance graphs.

## Conclusion

Using a genetic algorithm to optimize feature selection improves machine learning models for Breast cancer detection . This demonstrates the effectiveness of the approach in healthcare applications.
