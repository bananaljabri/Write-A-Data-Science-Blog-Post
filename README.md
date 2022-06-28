# Write-A-Data-Science-Blog-Post
Cardiac Ailment Prediction by Machine learning
https://medium.com/@banan.a.j/cardiac-ailment-prediction-by-machine-learning-f39f3084ada4
How we can utilization from health care industry data?
Can we discover hidden patterns or correlations among the objects in the medical data?
Can we predict cardiac ailment for each patient?

In this article, I take this research paper https://hal.archives-ouvertes.fr/hal-03371882 and try to analyze the data they used and implement the K-mean method.

The Libaray:
import pandas as pd
import numpy as np
#For visualizations
import matplotlib.pyplot as plt
import seaborn as sns
#conda install -c conda-forge/label/gcc7 missingno
import missingno as msno
import warnings
