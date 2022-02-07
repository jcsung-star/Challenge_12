![header](https://capsule-render.vercel.app/api?type=waving&color=gradient&width=1000&height=200&section=header&text=Logistic%20Regression%20Model%20Identify%20Credit%20Worthiness%20&fontSize=30&fontColor=black)

<!-- header is made with: https://github.com/kyechan99/capsule-render -->

[John Sung](https://linkedin.com/in/john-sung-3675569) [<img src="https://cdn2.auth0.com/docs/media/connections/linkedin.png" alt="LinkedIn -  John Sung" width=15/>](https://linkedin.com/in/john-sung-3675569/)
                                 
---

### Table of Contents

* [Overview](#overview)
* [Technoligies](#technologies)
* [Usage](#usage)
* [Sample Visualization and Metrics](#Sample-Visualization-and-Metrics)
* [License](#license)  


## Overview

In this program, I've used various techniques to train and evaluate models with imbalanced classes. You’ll use a dataset of historical lending activity from a peer-to-peer lending services company to build a model that can identify the creditworthiness of borrowers. You will be able to use a logistic regression model to compare two versions of the dataset, original and resampled. 

---

## Technologies

https://scikit-learn.org/stable/modules/generated/sklearn.linear_model.LogisticRegression.html

This project leverages python 3.7, imbalanced-learn and PyDotPlus libraries. You will install Install imbalanced-learn and PyDotPlus by installing in your conda dev environment in your terminal.

conda install -c conda-forge imbalanced-learn
conda install -c conda-forge pydotplus

---

## Usage

To use this application simply clone the repository and run credit_risk_resampling.ipynb on your Jupyter Notebook.

---

## Sample Visualization and Metrics

Value Counts for original dataset...
![y_v_cl](Images/y_value_counts.PNG)

Balance Accuracy, Confision Matrix & Classification Report of original dataset
![original](Images/original_data_results.PNG)

Value Counts for resampled dataset...
![y_r_v_cl](Images/y_resampled_value_counts.PNG)

Balance Accuracy, Confision Matrix & Classification Report of Resampled dataset
![resampled](Images/resampled_data_results.PNG)

---

## License

MIT

---
