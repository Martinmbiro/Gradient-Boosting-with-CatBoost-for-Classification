# Gradient Boosting with CatBoost for Classification

<p align="center">
  <img src='pics/cat.jpg'  width='530'/>
</p>

Hello again 👋
+ This tutorial is my take on implementing binary and multiclass classification using [`CatBoostClassifier`](https://catboost.ai/en/docs/concepts/python-reference_catboostclassifier) on two popular datasets; the [`penguins`](https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/ml-basics/penguins.csv) and [`diabetes`](https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/ml-basics/diabetes.csv) datasets
+ Since these are imbalanced datasets, I also demonstrate how to augment the training data using the [`imblearn`](https://imbalanced-learn.org/stable/index.html) library
+ The binary classification problem (using the [`diabetes`](https://raw.githubusercontent.com/MicrosoftDocs/mslearn-introduction-to-machine-learning/main/Data/ml-basics/diabetes.csv) dataset), being a medical diagnostics problem, I discuss why I choose certain evaluation metrics over others
+ Comments, working code, and links to the latest official documentation are included every step of the way
+ As always, feel free to build upon these concepts


## Milestones 🏁
**Concepts covered in this tutorial include:**  
1. [x] Data analysis and visualization
2. [x] Handling imbalanced datasets
3. [x] Training and evaluating classification models ([`CatBoostClassifier`](https://catboost.ai/en/docs/concepts/python-reference_catboostclassifier) & [`RandomForestClassifier`](https://scikit-learn.org/stable/modules/generated/sklearn.ensemble.RandomForestClassifier.html))
4. [x] Hyperparameter tuning with [`Optuna`](https://optuna.readthedocs.io/en/stable/index.html)

## Tools ⚒️
1. [`Google Colab`](https://colab.google/) - A hosted Jupyter Notebook service by Google.
2. [`pandas`](https://pandas.pydata.org/docs/index.html) - An open-source data analysis and manipulation tool built on Python
3. [`matplotlib`](https://matplotlib.org/) - A comprehensive library for making static, animated, and interactive visualizations in Python
4. [`seaborn`](https://seaborn.pydata.org/) -  A Python data visualization library based on [`matplotlib`](https://matplotlib.org/), that provides a high-level interface for drawing attractive and informative statistical graphics.
5. [`imblearn`](https://imbalanced-learn.org/stable/index.html) - A free and open-source Python library relying on [`scikit-learn`](https://scikit-learn.org/stable/#) that provides tools for dealing with classification problems that have imbalanced classes   
6. [`scikit-learn`](https://scikit-learn.org/stable/#) - A free open-source library that offers machine learning tools for the Python programming language
7. [`CatBoost`](https://catboost.ai/en/docs/) - An open-source machine learning algorithm that uses gradient boosting on decision trees
8. [`Optuna`](https://optuna.readthedocs.io/en/stable/index.html) - An automatic hyperparameter optimization software framework designed for machine learning

## Results 📈
+ The final _binary classification_ model achieved a weighted `recall`, `f1 score` & `precision` of `0.95`, and overall `accuracy` of `0.95`. The Area Under Curve `(auc)` was `0.99`
+ The final _multiclass classification_ model achieved a weighted `recall`, `f1 score` & `precision` of `0.98`, and overall `accuracy` of `0.98`. The average Area Under Curve `(auc)` was `0.99`
+ Both models can be found in the `models` folder of the current repository

## Reference 📚
+ Thanks to the insight gained from the [`Microsoft Learn`](https://learn.microsoft.com/en-us/) [`learning path`](https://learn.microsoft.com/en-us/training/browse/?resource_type=learning%20path) linked [`here`](https://learn.microsoft.com/api/achievements/share/en-us/MartinMuriithi-6560/NZ987NAF?sharingId=C156514E494249EC)
+ Not forgetting [`datacamp`](https://www.datacamp.com), [`medium`](https://medium.com) and these gorgeous [`emojis`](https://gist.github.com/FlyteWizard/468c0a0a6c854ed5780a32deb73d457f) 😻


> _In loving memory of Jess - best cat that ever lived_  ♥
