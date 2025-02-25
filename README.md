# Marketing Spending Analysis

## 🔍 Project Overview  
This project analyzes marketing spending to evaluate the effectiveness of various marketing campaigns and identify actionable insights for improving business outcomes.

## 🎯 Objectives  
- Analyze overall **Return on Marketing Investment (ROMI)** and ROMI by campaign.  
- Assess performance metrics based on **spending, revenue, and conversion rates**.  
- Conduct **clustering analysis** to segment campaigns and identify patterns in performance, allowing for targeted marketing strategies and optimized resource allocation.  

📌 *Note:* To view the interactive **Plotly** graphs, please run the corresponding code cells.  

## 📂 Dataset Description  
The dataset includes the following information:  
- **Date**: Date of marketing budget spending.  
- **Campaign Name**: Description of the campaign.  
- **Category**: Type of marketing source (e.g., influencer, social media).  
- **Campaign ID**: Unique identifier for the campaign.  
- **Impressions**: Number of times the ad was shown.  
- **Clicks**: Number of times users clicked on the ad.  
- **Conversions**: Number of successful actions taken by users (e.g., purchases, sign-ups).  
- **Spend**: Amount spent on the campaign.  
- **Revenue**: Total revenue generated from the campaign.  

## 📊 Analysis & Methodology  
- **ROMI Calculation**: Analyzing **return on marketing investment** for different campaigns.  
- **Cost-Metric Comparisons**: Evaluating **CPC (cost per click)**, **CPL (cost per lead)**, and **CAC (customer acquisition cost)**.  
- **Heatmap Analysis**: Identifying the **best and worst-performing campaigns** based on ROMI and conversion rates.  
- **Clustering (K-Means)**: Segmenting campaigns into **four clusters (k=4)** to analyze common trends and patterns.  
- **Trend Analysis**: Evaluating campaign performance over time for different marketing categories.  

## 🛠️ Tech Stack  
- **Python**  
- **Pandas & NumPy** (Data manipulation & analysis)  
- **Matplotlib & Seaborn** (Data visualization)  
- **Plotly** (Interactive charts)  
- **Scikit-learn** (Clustering & ML models)  
- **SQL** (Querying campaign performance)  

## 🚀 Results & Insights  
- Campaigns with **higher CPC** don’t always yield **better ROMI**.  
- Influencer campaigns had **higher engagement** but **lower conversion rates** than paid search campaigns.  
- Cluster analysis revealed **four distinct campaign groups** based on performance.  
- Seasonal trends influenced **conversion rates and ROMI variations**.  

## 📌 How to Use  
1. Clone this repository:  
   ```bash
   git clone https://github.com/Shrutaswini/Marketing-spending-analysis.git
2. Install required dependencies:
bash - 
Copy -
Edit -
pip install pandas numpy matplotlib seaborn plotly scikit-learn
3. Open the Jupyter notebook and run the cells to explore the analysis.

## 📜 License
This project is open-source and available under the MIT License.


