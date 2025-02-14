#  Fraud Detection in Bank Transactions

This repository contains an **exploratory data analysis (EDA)** project focused on detecting fraud in bank transactions. The project leverages data visualization, preprocessing, and unsupervised clustering techniques to uncover patterns and identify potentially fraudulent transactions.

## Project Overview

- **Objective:**  
  Analyze bank transaction data to identify trends and anomalies indicative of fraudulent behavior using EDA and clustering techniques.

- **Approach:**  
  - **Data Cleaning & Preprocessing:** Handled missing values, encoded categorical variables, and normalized the data.
  - **Exploratory Analysis:** Visualized distributions, temporal patterns, and correlations in the transaction data.
  - **Clustering Analysis:** Applied the DBSCAN clustering algorithm to group similar transactions and isolate outliers as potential fraud.

## Key Steps in the Analysis

1. **Data Preprocessing:**  
   - **Cleaned** the dataset by addressing missing values and outliers.  
   - **Transformed** categorical features and normalized numerical variables.

2. **Exploratory Data Analysis:**  
   - **Visualized** transaction trends and distributions using histograms and box plots.
   - **Examined** temporal patterns and feature correlations to identify irregularities.

3. **Clustering & Fraud Detection:**  
   - **Applied** the DBSCAN clustering algorithm to segment the dataas the optimal model over K-Means, Agglomerative Clustering, One-Class SVM, and Isolation Forest, due to its superior ability to detect anomalies in high-density data regions.    
   - **Evaluated** clustering performance using the silhouette score.  
   - **Identified** key outlier clusters indicative of potential fraud.


### **Outcome**  
- **Identified** a total of **6 fraudulent transactions** in the dataset through clustering analysis.  
- **Achieved** a **Silhouette Score of 0.33064**, indicating moderate clustering performance.  
- **Selected** **DBScan Clustering** as the optimal model 


## Data

- **Dataset:**  
  This analysis is based on a bank transactions dataset containing features such as transaction amounts, dates, transaction types, and a fraud indicator.

- **Source:**  
  Inspired by a Kaggle notebook by [mllion](https://www.kaggle.com/code/mllion/bank-transaction-eda-for-fraud-detection/notebook).

## Technologies & Libraries

- **Python** – Core programming language.
- **Pandas & NumPy** – Data manipulation and numerical operations.
- **Matplotlib & Seaborn** – Data visualization.
- **Scikit-learn** – Implementing DBSCAN and evaluating the clustering performance.
- **Jupyter Notebook** – Interactive environment for analysis.

## How to Run the Project

1. **Clone the Repository:**

   ```bash
   git clone https://github.com/AIShaktiNeil/Fraud-Detection/blob/main/US_bank_anomalyDetection.ipynb?short_path=0e8055c
   cd bank-transaction-eda-fraud-detection
   ```

2. **Install Dependencies:**

   Ensure you have Python installed, then run:

   ```bash
   pip install -r requirements.txt
   ```

3. **Launch the Notebook:**

   Start Jupyter Notebook and open the project file:

   ```bash
   http://localhost:8888/lab/tree/Downloads/US_bank_anomalyDetection.ipynb
   ```

4. **Execute the Analysis:**

   Run the notebook cells sequentially to reproduce the EDA and clustering results.

## Contributing

Contributions are welcome! If you have suggestions or improvements, please feel free to open an issue or submit a pull request.

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

## Acknowledgements

- Special thanks to the original Kaggle author [mllion](https://www.kaggle.com/mllion) for the inspiration and foundation of this analysis.
- Thanks to the Kaggle community for their support and shared knowledge in fraud detection research.
