Jupyter Notebook user guide
=====================================================

This guide outlines the steps required to run the Jupyter Notebook provided in this directory.

Prerequisites
---------

- Have a version of Python installed on your machine
- Have selected a Jupyter environment

Install the necessary packages
-------------------------------------

To run the notebook, you need to install certain Python packages. You can do this using the following commands:

`pip install -U scikit-learn`
`pip install seaborn`
`pip install xgboost`

Running the notebook
---------------------

Once the packages have been installed, you can run the notebook by opening the file `Projet_Machine_Learning.ipynb` in Jupyter Notebook.

Data prediction
---------------------

If you want to predict data, you can run the `Projet_Machine_Learning_trained_models.ipynb` file in Jupyter Notebook.

We've saved our two best-performing models (one for regression and one for classification).

You can enter house features in two different ways:

- If you want to predict the price of a house only, you can fill in the necessary house features in the np.array of cells associated with the models.

- If you want to predict the price of several houses, you can fill in the data_to_predict.csv file in the data folder, then run the cells associated with the models.

A `data_description.txt` file is available for you to select characteristic values to estimate the price of your house(s).Good luck with your predictions!
