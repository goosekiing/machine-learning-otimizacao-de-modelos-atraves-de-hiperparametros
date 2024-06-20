# Machine Learning: Hyperparameter Optimization

This repository contains a project focused on evaluating how the variation of hyperparameters affects a machine learning model designed to predict whether a car will be sold based on variables such as mileage, model year, and price. The project uses a for loop to test models from scikit-learn with varying hyperparameters. Using pandas and seaborn, the results are analyzed to find the hyperparameter combination that offers the highest accuracy. Parameters such as `max_depth`, `min_samples_leaf`, and `min_samples_split` of the `DecisionTreeClassifier` model are varied and refined through several tests to achieve satisfactory parameters, aiming to reduce the risk of overfitting.

## Project Overview
The goal of this project is to optimize a machine learning model by exploring different hyperparameters and understanding their impact on model performance. This involves systematic testing and refinement of hyperparameters to achieve the best possible model accuracy.

## Course Details
This project was completed as part of the Machine Learning course on Alura. For more information about the course, visit [Alura](https://cursos.alura.com.br/formacao-machine-learning-v64177).

## Objectives Achieved
- Understand hyperparameters and parameter spaces.
- Explore parameter spaces deterministically.
- Optimize machine learning models.
- Avoid overfitting.
- Implement behind-the-scenes exploration.
- Use GridSearchCV for hyperparameter exploration.
- Apply nested cross-validation.

## Technologies Used
- Python
- Jupyter Notebook
- Pandas
- NumPy
- Scikit-learn
- Seaborn

## Project Structure
The directory structure of the project is as follows:
```
machine-learning-otimização-de-modelos-através-de-hiperparâmetros/
│   project-1-data.csv
│   project-1.ipynb
│   README.md
```

## How to Run the Project
1. Clone the repository:
   ```sh
   git clone https://github.com/goosekiing/machine-learning-otimizacao-de-modelos-atraves-de-hiperparametros.git
   ```
2. Navigate to the project directory:
   ```sh
   cd machine-learning-otimizacao-de-modelos-atraves-de-hiperparametros
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook project-1.ipynb
   ```

## Learn More
To learn more about hyperparameter optimization and machine learning, visit the course page on [Alura](https://cursos.alura.com.br/formacao-machine-learning-v64177).

Feel free to explore, modify, and use this project as a foundation for your own machine learning projects!

## Language
The language used in this project is Brazilian Portuguese (pt-br).
