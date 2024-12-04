# Project Title
Reservoir-Characterization
## Project Description
This project is focused on applying Machine learning techniques towards understanding the subsurface properties and behavior of oil and gas reservoirs thereby enhancing reservior characterization.
## Installation Instructions
git clone <repo-url>
cd <project-directory>
pip install -r requirements.txt
## How to Use

## Data
The data is from the UNiversity of Kansas class exercise on  the Hugoton and Panoma gas fields.
The data is in csv format and is uploaded to this repository

## Model description
ML models used in this project are Support VEctor Machine, KNN, DecisionTree, Random Forest and Gradient Boosting

## Training Process
To train the model we performed label encoding on the 'Formation', 'Well Name' and 'FaciesLabels' and Standardization of numerical columns

## Evaluation
We evaluated the performance of the model using the accuracy scores, precision, recall, F1-score and support


## Results
The best performing model is RandomForest with an average accuracy score of 81% after cross validation.




## References


Dubois et al. (2007) http://github.com/seg.[1]

Amato del Monte, A., 2015. Seismic Petrophysics: Part 1, The Leading Edge, 34 (4). doi:10.1190/tle34040440.1

Bohling, G. C., and M. K. Dubois, 2003. An Integrated Application of Neural Network and Markov Chain Techniques to Prediction of Lithofacies from Well Logs, KGS Open-File Report 2003-50, 6 pp. pdf

Dubois, M. K., G. C. Bohling, and S. Chakrabarti, 2007, Comparison of four approaches to a rock facies classification problem, Computers & Geosciences, 33 (5), 599-617 pp. doi:10.1016/j.cageo.2006.08.011

