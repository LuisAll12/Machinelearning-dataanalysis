# Machine Learning & Dataanalysis
##### 21.02.2025 Luzern
---

This project was motivated by my ÜK grade, which suffered due to a misunderstanding—I built two models for two problems instead of one. My teachers were strict with their feedback, pushing me to prove myself again. Additionally, I took on this challenge out of personal interest.

***
## Contents
* How to download
* Usage


---

## How to download

Download it with the following command:
- ```git clone <repository link>```


If your done with this step follow the instruction for the usage to make it work.

---

## Usage

### Documentation(PDF)
##### The Documentation contains the EDA, Hypotheses, Models and the Summary

**EDA:**
The EDA(Exploratory Data Analysis) is the process of analyzing and summarizing a dataset to understand its key characteristics before applying machine learning models or statistical methods. It helps in detecting patterns, spotting anomalies, and checking assumptions using visualizations and summary statistics.

**Hypotheses:**
This study examines three hypotheses related to physical performance, body composition, and age-related health indicators. Using data analysis, correlation matrices, and machine learning models, the study explores the relationships between grip strength, body fat percentage, flexibility, and blood pressure.

**Models:**
Each model was used to test a hypothesis by identifying key relationships in the data. While some models provided strong evidence for a hypothesis (e.g., gender and grip strength), others (e.g., age and blood pressure) showed that additional variables are needed for accurate predictions.

**Summary:**
Each model tested a hypothesis by analyzing key data relationships. While the first confirmed flexibility as a stronger predictor than body fat, the second validated the link between gender and grip strength with high accuracy. The third showed age alone is insufficient to predict blood pressure. Despite varying results, the models provided valuable insights.

### Python Notebook(ipynb)

**Description:**
This project deals with the analysis of body performance data and the creation of prediction models to explore relationships between various physical attributes and the classification of individuals. Using data such as height, weight, grip strength, sit-ups, long jump distance, and body fat percentage, models are trained to predict classifications such as gender and physical fitness.

The project also includes the creation of visualizations to analyze the data and its correlations. You can examine the key relationships between variables using graphs and heatmaps.

**Usage:**
- **Data Preparation**: The CSV file `bodyPerformance.csv` contains the required data. In this project, duplicate data is detected and cleaned.  
- **Data Visualization**: Various graphs are generated, such as scatter plots, box plots, and histograms, to analyze the distribution of the data and correlations.  
- **Modeling**: Different machine learning models like Random Forest, XGBoost, and Voting Classifiers were used to test accuracy in predicting classifications (e.g., gender and fitness). A linear regression model was created to analyze the relationship between age and blood pressure.
**Note**: You do not need to run the project anymore, as all graphics have already been generated and the models have been tested. The visualizations and model accuracies are already included in the code.

