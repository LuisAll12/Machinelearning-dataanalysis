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

**Beschreibung:**
Dieses Projekt befasst sich mit der Analyse von Körperleistungsdaten und der Erstellung von Vorhersagemodellen, um Zusammenhänge zwischen verschiedenen physischen Eigenschaften und der Klassifikation von Personen zu untersuchen. Mithilfe von Daten wie Körpergröße, Gewicht, Griffkraft, Sit-ups, Weitsprungweite und Körperfettanteil werden Modelle trainiert, um Klassifikationen wie Geschlecht und körperliche Fitness vorherzusagen.

Das Projekt umfasst auch die Erstellung von Visualisierungen zur Analyse der Daten und deren Korrelationen. Du kannst die wichtigsten Beziehungen zwischen Variablen mithilfe von Grafiken und Heatmaps untersuchen.

**Benutzung:**
Datenvorbereitung: Die CSV-Datei bodyPerformance.csv enthält die benötigten Daten. In diesem Projekt werden duplizierte Daten erkannt und bereinigt.
Datenvisualisierung: Es werden verschiedene Grafiken generiert, wie z.B. Scatterplots, Boxplots und Histogramme, um die Verteilung der Daten und die Korrelationen zu analysieren.
Modellierung: Verschiedene Machine-Learning-Modelle wie Random Forest, XGBoost und Voting-Klassifikatoren wurden verwendet, um die Genauigkeit bei der Vorhersage von Klassifikationen (z.B. Geschlecht und Fitness) zu testen. Ein lineares Regressionsmodell wurde zur Analyse des Zusammenhangs zwischen Alter und Blutdruck erstellt.
Hinweis: Du musst das Projekt nicht mehr ausführen, da alle Grafiken bereits generiert wurden und die Modelle getestet wurden. Die Visualisierungen und die Modellgenauigkeiten sind bereits im Code enthalten.


