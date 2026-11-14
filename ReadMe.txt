# DSC8307 Data Mining, Modelling and Analytics – Assignment 2

Notebooks - project1_wholesale.ipynb and project2_creditcard.ipynb
Dataset - Segmenting wholesale customers by spending behaviour wholesale-customers.csv and Credit card fraud detection as anomaly ranking creditcard.csv (stored as four compressed parts, creditcard_part*.csv.gz)

# How to run
 -Clone this repository (the data files are in the repository root, next to the notebooks).
 -Install the dependencies (Python 3.10 or later): - pip install -r requirements.txt
 -Open each notebook in VS Code and choose **Run All**. Each notebook runs from top to bottom in a few minutes
 -The credit card file (150 MB) is too large for GitHub, so it is split into four compressed parts. The notebook reads creditcard.csv if it is present, otherwise it joins the parts automatically

## Data sources

- Wholesale Customers: UCI Machine Learning Repository. M. Cardoso (2014), *Wholesale customers*.
- Credit Card Fraud Detection: Kaggle, collected by Worldline and the Machine Learning Group of ULB. A. Dal Pozzolo, O. Caelen, R. A. Johnson and G. Bontempi (2015), "Calibrating Probability with Undersampling for Unbalanced Classification", *IEEE Symposium on Computational Intelligence and Data Mining (CIDM)*.
