# 02807-Computational_Tools_for_Data_Science

## Crash Cause - Correlation and Data-Driven Analysis of Road Accidents 🎯
Despite continuous improvements in vehicle safety and infrastructure, road accidents remain a leading cause of death and injury worldwide. Understanding how factors like vehicle type, weather, and road conditions interact—and which combinations predict fatal outcomes—is essential for effective prevention.Large datasets have been studied, revealing combinations of factors linked to severe or fatal crashes. This project uncovers key correlations and patterns between accident characteristics and severity, emphasizing risk factors that contribute most to fatalities. These insights could help authorities prioritize life-saving interventions.

Our research questions are:

1. Can classical data mining and machine learning methods uncover latent relationships between driver, vehicle, and environmental factors in fatal crashes?
2. Can advanced data science techniques reveal the importance of these factors in fatal outcomes?


## Installation ⬇️

To run this project locally, follow these steps:

### Prerequisites

Ensure you have Python installed (preferably Python 3.12 or later).

### Setup

1. Clone the repository:
   ```sh
   git clone https://github.com/RupakKadhare15/02807-Computational_Tools_for_Data_Science.git
   ```
2. Change the directory:
   ```sh 
   cd 02807-Computational_Tools_for_Data_Science
   ```
3. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```
   
## Usage & Procedure
After installation of the requirements files and dataset, follow the procedures below to reproduce the analysis. The project is divided into two main parts: FARS (Clustering & Frequent Itemsets) and CRSS (Regression & Trend Analysis).

### FARS Analysis (Clustering & Frequent Itemsets)
This section focuses on the Fatal Accident Reporting System (FARS) data. It covers data extraction, feature engineering, clustering and association rule mining (Apriori).

1. Input Data: The notebooks utilize the datasets located in the [Dataset](Dataset) folder.
2. Outputs: Visualizations and processed files are saved to the [Results](Results) under Optimal_K, Individual_Cluster_Results, and St4_apriori_results.

#### Execution Steps
1. [FARS_step1_data_extraction.ipynb](FARS_step1_data_extraction.ipynb) : Run this to extract and consolidate the raw data.
2. [FARS_step2_feature_engineering.ipynb](FARS_step2_feature_engineering.ipynb) : Performs preprocessing and transforms the data for analysis.
3. [FARS_step3_clustering.ipynb](FARS_step3_clustering.ipynb) : Executes the clustering algorithms to identify accident patterns.
4. [FARS_step4_Apriori_Scratch_with_mlxtend.ipynb](FARS_step4_Apriori_Scratch_with_mlxtend.ipynb) : Runs the Apriori algorithm to find frequent itemsets and association rules within the clusters.

### CRSS Analysis (Regression)
This section focuses on the Crash Report Sampling System (CRSS) data.

1. Input Data: The notebooks utilize the regression dataset located in [Dataset_Regression](Dataset_Regression) folder.
2. Outputs: Analysis results are stored in the [CRSS_Analysis](CRSS_Analysis) directory.

#### Execution Steps
1. [CRSS_Step1_data_extraction.ipynb](CRSS_Step1_data_extraction.ipynb) : Handles the initial data loading and preparation for the CRSS dataset.
2. [CRSS_Step2_Analysis.ipynb](CRSS_Step2_Analysis.ipynb) : Performs the regression analysis and generates the final insights.
   
## Dataset 📊
The original datasets can be accessed using the given links:

FARS: https://www.nhtsa.gov/file-downloads?p=nhtsa/downloads/FARS/2023/National/
- On the website, download *FARS2023NationalCSV.zip*
- Add the following files to *Dataset* folder: vehicle, person, accident

CRSS: https://www.nhtsa.gov/file-downloads?p=nhtsa/downloads/CRSS/2023/ 

## Authors 🧑🏻‍💻 

[Trinity Evans](https://github.com/trinception)  ,
[Omar Gonzalez](https://github.com/OmarGGH) , 
[Rupak Kadhare](https://github.com/RupakKadhare15) , 
[Brynjar Bjarkason](https://github.com/brynjar13) 
