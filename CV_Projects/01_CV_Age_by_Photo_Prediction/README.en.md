[![ru](https://img.shields.io/badge/lang-ru-red.svg)](README.md)

# Customer age prediction by photo. 

## Problem.
Building a model that will determine the approximate age of a person from a camera photo in the checkout area to generate product suggestions and an additional method of controlling cashiers when selling alcohol.
## Solution.
ResNet50 model was built with initialization of imagenet weights and specified “head”.<br>
The final value of the target metric, mean absolute error, is 6.33, which is below the minimum threshold of 8 years and is a good result.

[Project permalink.](https://github.com/mrBrain101/Yandex_Practicum_projects/blob/408c01a5fbc909cd6242e32a788c9d313d3c4490/CV_Age_by_Photo_Prediction/Ya_Practicum_ML_Age_by_Photo_distr_RUS.ipynb)

## Steps:
<li>EDA. 
<li>Preprocessing. 
<li>Models validation ant testing.
  
## Utilized libraries and tools:
<li>Tensorflow.
<li>PIL.
<li>Pandas. 
<li>Matplotlib. 
<li>Seaborn. 
<li>Numpy. 
