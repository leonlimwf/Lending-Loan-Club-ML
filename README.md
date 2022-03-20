
## Brief Background

An US bank would like to improve its financial performance with regards to approval of new loans. There are probably too many people that defaulted on the loan and might cost the bank money in certain scenarios. but not every defaulters is a loss

### Install

This project requires **Python** and the following Python libraries installed:

- [NumPy](http://www.numpy.org/)
- [Pandas](http://pandas.pydata.org/)
- [matplotlib](http://matplotlib.org/)
- [scikit-learn](http://scikit-learn.org/stable/)
- [plotly](https://plotly.com/python/)
- [shap](https://shap.readthedocs.io/en/latest/index.html)

You will also need to have software installed to run and execute a [Jupyter Notebook](http://jupyter.org/install.html).

If you do not have Python installed yet, it is highly recommended that you install the [Anaconda](https://www.anaconda.com/download/) distribution of Python, which already has the above packages and more included. 

### Run

```bash
ipython notebook lending_loan_club.ipynb
```  
or
```bash
jupyter notebook lending_loan_club.ipynb
```
or open with Jupyter Lab
```bash
jupyter lab
```

This will open the Jupyter Notebook software and project file in your browser.

### Data

The dataset can be found at (https://www.kaggle.com/wordsforthewise/lending-club). As this is a school project, some numbers would be changed to ensure students do not plagiarize from the website itself.

**Algorithms Used (Under project's rules)**

1. Random Forest Classifier
2. Decision Tree Classifier

**Metrics Used (Under project's rules)**

1. Precision
2. Recall
3. F1 Score
4. MCC

**Target Variable**

4. loan_status
