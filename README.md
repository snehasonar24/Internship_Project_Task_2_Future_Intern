**Titanic Dataset Summary and Analysis**

**Overview**

This document provides an overview of the analysis conducted on the Titanic dataset, including a summary of statistics for key features, visualization, and insights derived from the data. 
The dataset used for this analysis is tt_cleaned, which contains passenger information from the Titanic dataset.

**Dataset Description**

The tt_cleaned dataset contains the following columns:

* Survived: Indicates whether the passenger survived (1) or not (0).
* Pclass: Passenger's class 
* Age: Passenger's age.
* SibSp: Number of siblings or spouses aboard.
* Parch: Number of parents or children aboard.
* Fare: Fare paid by the passenger.

**Summary Statistics**

We calculated various summary statistics for each feature in the dataset. The following metrics were computed:

* **Mean:** The average value of the feature.
* **Median:** The middle value of the feature.
* **Mode:** The most frequent value of the feature.
* **Standard Deviation:** A measure of the dispersion of values in the feature.
  
**Data Visualization:**

Uses Pandas styling to create visually appealing tables with background gradients for summary statistics.

Provides an overview of metrics using the Spectral and viridis colormaps for gradient representation.

**Insights and Conclusions**

* **Survival Rate:** The average survival rate is low, indicating that most passengers did not survive.
* **Passenger Class:** The majority of passengers were in lower classes (2 and 3), which could be associated with lower survival rates.
* **Age Distribution:** The dataset shows a wide range of ages among passengers, suggesting diverse demographics.
* **Fare Paid:** The fare distribution shows significant variation, with a broad range of values.
* **Family Members:** Most passengers had few or no family members aboard, as indicated by the low values in the SibSp and Parch columns.
