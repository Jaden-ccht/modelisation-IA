Réalisation d’une intelligence artificielle permettant la reconnaissance de kystes et ganglions bénins, graves ou normaux à partir d'images d’échographies mammaires et de masques binaires leur correspondant.
Ce projet a été réalisé en DUT informatique, en binôme.

Bibliothèques utilisées :

import pandas as pd
import numpy as np
import matplotlib.image as im
import matplotlib.pyplot as plt
import cv2

from os import listdir
from sklearn.model_selection import train_test_split, GridSearchCV
from sklearn.tree import DecisionTreeClassifier
from sklearn import metrics, svm
from sklearn.metrics import classification_report, accuracy_score
from sklearn.neighbors import KNeighborsClassifier
from mpl_toolkits.axes_grid1 import make_axes_locatable


Lien du dataset :
https://www.kaggle.com/aryashah2k/breast-ultrasound-images-dataset
