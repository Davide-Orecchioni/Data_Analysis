# Data Analysis
Material for my final project for the 2025 Data Analysis master's course at the University of Pisa, held by prof. Marco Romito and prof. Katerina Papagiannouli. More information about the course can be found at https://people.dm.unipi.it/romito/Teaching/2025/data.

The final task for the Data Analysis course was to create a classifier that can distinguish between five strains (one wild-type, four mutant) of Caenorhabditis elegans. The provided dataset contains time series data of the first six principal components of the motion of a few worm specimens on agar plates. The main challenge of the task was to deal with
- the difficulty of interpretation of such highly processed data;
- the high intercorrelation and redundance of features typical of time series data;
- the computational challenges of using classical methods on data with high dimension;
- the unbalance between classes and the presence of artificial outliers, caused by the use of improper processing methods by the original creators of the dataset in the measurement and recording phase.

The repository contains the following files:
- ```AD.pdf``` is the final report;
- ```FinalTask.ipynb``` is a Python notebook with the code and figures used for the final report;
- ```FinalTask.pdf``` is the original assignment for the course, with more information on the dataset and related material.
