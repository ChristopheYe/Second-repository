# DM2-ML : Randomized optimization

URL to have access to all the codes and the dataset : https://github.com/ChristopheYe/Second-repository.git

I. PROJECT'S TITLE

DM2 ML

II. PROJECT DESCRIPTION

The code is written with Python on different Jupyter Notebook
In addition of many classic libraries like numpy and matplotlib, I used mlrose_hiive and sklearn libraries :
import numpy as np
import time
import pandas as pd
import io
import matplotlib.pyplot as plt
import mlrose_hiive
from sklearn.model_selection import train_test_split
from sklearn.metrics import accuracy_score
from sklearn.model_selection import cross_val_score
from sklearn.preprocessing import LabelEncoder, MinMaxScaler


First part : Experimentation with 4 different randomized optimization algorithm
1. Random Hill Climbing
2. Simulated annealing
3. Genetic algorithm
4. Mimic

I used these 4 algorithms on 3 different problems :
1. Flip Flop
2. Four peaks
3. knapsack

Second part : Randomized optimisation algorithm applied on Neural Network
Dataset used : Movie Dataset.csv
I want to know if a movie got an award or no and I will try which randomized optimization algorithm performs the best.

III. HOW TO INSTALL AND RUN THE PROJECT

1. Import all the libraries
2. Run all the different codes in the GitHub
