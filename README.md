# DecisionTree-Classification_reaserch

This repository contains files for a project employing feature extraction method called Principal Component Analysis (PCA) with a parameter setting of n_components=25, and SelectKBest feature selection technique using the F-classification (f-classif) scoring function with k=10 as the number of selected features. For classification purposes, this project assess the performance of the Decision Tree Classifier.

In this project, I experimented with different configurations of the Decision Tree Classifier, varying the maximum depth parameter with values of 5, 10, and 20. Additionally, I tested the classifier with and without specifying the maximum number of features to consider at each split, setting max_features="sqrt".

**Requirements**

* Python (version 3.6 or later): [https://www.python.org/downloads/](https://www.python.org/downloads/)
* Jupyter:  
  Open a project in a python soporter IDE such as pycharm / VSCode, that will contains this project pages, and use the chosen IDE's terminal to run your commands:
  * For **Notebook** version, Install using:
    * `pip install jupyter`  
  * For the **Lab** version, Install using:
    * `pip install jupyterlab`
  
  A window will open in your home browser where it will be possible to run the code and also create new documents as you wish. For more instructions: [https://jupyter.org/](https://jupyter.org/).  
* Required libraries:
    * NumPy ([https://numpy.org/](https://numpy.org/))
    * Matplotlib ([https://matplotlib.org/](https://matplotlib.org/))
    * scikit-learn ([https://scikit-learn.org/](https://scikit-learn.org/))
        * `sklearn.datasets` for loading the Covertype dataset
        * `sklearn.decomposition` for PCA
        * `sklearn.feature_selection` for SelectKBest (with F-Classif)
        * `sklearn.model_selection` for data splitting
        * `sklearn.tree` for DecisionTreeClassifier
        * `sklearn.metrics` for accuracy scores
    * time ([https://docs.python.org/3/library/time.html])

**Usage**

1. Clone this repository:

   ```bash
   git clone https://github.com/shakedasido/Feature_Extraction_and_Selection_methods
   ```

2. Launch Jupyter Notebook OR Jupyter Lab:

   Jupyter Notebook:

   ```bash
   jupyter notebook
   ```

   Jupyter Lab:


   ```bash
   jupyter lab
   ```

4. Open the Jupyter Notebppk files (`.ipynb` extension) at the chosen enviroment, one by one, and execute the code cells (typically by pressing `Shift+Enter`). These notebooks guide you through the analysis steps:
    * **Data Loading and Preprocessing**
    * **Feature Extraction with PCA and Feature Selection with SelectKBest and F-classif**
    * **Classification with DecisionTreeClassification**
    * **Evaluation with Time efficiency, Mean accuracy and K-Fold Cross-Validation Scores**

**Results**

The notebooks will display results of the Evaluation with Time efficiency, Mean accuracy and K-Fold Cross-Validation Scores finded for the chosen parameters. more information about it you can find in this PDF file:  
[DecisionTree-Classification_reaserch.pdf](https://github.com/shakedasido/DecisionTree-Classification_reaserch/files/14938189/DecisionTree-Classification_reaserch.pdf)


**Additional Notes**

* This project assumes the Covertype dataset has 7 unique classes.
* You can experiment with different values to potentially improve performance.

Enjoy exploring the project and feel free to ask questions about it through its comments! 

