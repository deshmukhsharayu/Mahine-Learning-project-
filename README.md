Mobile Price Classification

*📘 Overview

This project aims to predict the price range of mobile phones based on various features such as battery power, RAM, screen size, etc.
Using Machine Learning, we analyze the training dataset and build a model that can classify mobiles into different price categories.

*📂 Dataset Information

We are using the Mobile Price Classification dataset available on Kaggle.

*Training Dataset:
/kaggle/input/mobile-price-classification/train.csv
Contains the features of mobile phones and their corresponding price ranges.

*Test Dataset:
/kaggle/input/mobile-price-classification/test.csv
Contains similar features but without price labels (used for predictions).

Dataset Description

*train.csv columns:

battery_power: Total energy a battery can store (mAh)

blue: Bluetooth (1 = Yes, 0 = No)

clock_speed: Speed at which microprocessor executes instructions

dual_sim: Supports dual sim (1 = Yes, 0 = No)

fc: Front Camera megapixels

int_memory: Internal memory (GB)

mobile_wt: Weight of mobile (grams)

n_cores: Number of cores in processor

ram: Random access memory (MB)

talk_time: Maximum time one battery charge will last

price_range: Target variable (0 = low cost, 1 = medium cost, 2 = high cost, 3 = very high cost)

*Project Steps

Import libraries and load datasets.

Explore and visualize the data (EDA).

Preprocess data — handle missing values, normalization, feature selection.

Train machine learning models (e.g., Decision Tree, Random Forest, SVM).

Evaluate performance using accuracy, precision, recall, and F1-score.

Predict price range on test dataset.

*Output

Model accuracy score.

Predicted price ranges for test data.

*💡 Tools & Libraries

Python

Pandas

NumPy

Scikit-learn

Matplotlib / Seaborn

*test.csv columns:
Same as above, except price_range (no target column).
