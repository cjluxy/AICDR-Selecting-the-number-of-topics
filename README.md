# AICDR：Selecting the number of topics
This project implements the AICDR of Xu and Zhou  for selecting the number of topics. Paper Title: “An adaptive method for determining the optimal number of topics in topic modeling”.

# Some advantages of this algorithm: 

AICDR is a technique predicated on clustering results to select the optimal number of topics and has strong adaptability to various topic models. 
It doesn't need complex parameters and responds quickly. ﻿ This project is an easy to read reference implementation of AICDR.

# How to use
1. Firstly, use the Topic models.ipynb file to classify the dataset according to the number of different topics, and upload the classification results to the output folder.
2. Use the metrics.ipynb file to calculate AICDR on the results in the output folder and determine the number of topics. Metrics. ipynb includes the Elbow Method and AQDEB method.
3. The Stability Analysis. ipynb file is an implementation of the comparative method Stability Analysis.
4. The output folder stores the results of various method runs.
