**Crypto Trader Behavior Analysis** 

**Project Description**

This project analyzes crypto trader behavior by integrating historical trade data with sentiment (Fear & Greed Index) data. It aims to identify patterns, segment traders based on their trading characteristics, and understand how market sentiment influences their performance.

**Deliverables**

Trader Performance vs Market Sentiment.ipynb: The Jupyter Notebook containing all the code and analysis.

README.md: This file, detailing setup and how to run the project.

Output Charts/Tables: Visualizations generated within the notebook illustrating key findings.

Summary Write-up: A markdown section within the notebook (or a separate file) summarizing methodology, insights, and strategy recommendations.

**Setup and How to Run
Clone the Repository:**
git clone <your-repo-link>
cd <your-repo-name>

**Data Files:** Ensure the following CSV files are in the same directory as the notebook:
fear_greed_index (1).csv
historical_data (1).csv

**Open in Google Colab:**
Go to [google colab].
Click on File > Upload notebook and upload crypto_trader_analysis.ipynb.
Alternatively, File > Open notebook > GitHub and paste your repository URL.

**Install Dependencies:** Google Colab typically has pandas, seaborn, and matplotlib pre-installed. If not, you can install them using:
!pip install pandas seaborn matplotlib

**Run the Notebook:** Execute the cells sequentially from top to bottom. The notebook is structured with sections for data loading, cleaning, metric creation, merging, analysis, and segmentation. The charts will be displayed inline.

**Analysis Overview**
The notebook performs the following key steps:

**Data Loading & Cleaning:** Loads historical trade data and fear/greed index, cleans column names, converts data types, and handles duplicates.

**Key Metrics Calculation:** Computes daily PnL, trade count, and average trade size per account.

**Sentiment Integration:** Merges trading metrics with daily market sentiment classifications.

**Initial Analysis:** Explores relationships between sentiment and trading performance/behavior.

**Trader Segmentation:** Categorizes traders into High/Low Leverage (using 'Size Tokens' as proxy), Frequent/Infrequent, and Consistent Winners/Inconsistent Traders.
