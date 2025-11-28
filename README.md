# YOUTUBE-TRENDING-VIDEOS-IN-NIGERIA
Exploratory Data Analysis On Youtube Trending Videos In Nigeria (2023-2025)
![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54)
![Pandas](https://img.shields.io/badge/pandas-%23150458.svg?style=for-the-badge&logo=pandas&logoColor=white)
![Matplotlib](https://img.shields.io/badge/Matplotlib-%23ffffff.svg?style=for-the-badge&logo=matplotlib&logoColor=black)
![Seaborn](https://img.shields.io/badge/Seaborn-3776ab?style=for-the-badge&logo=python&logoColor=white)
![Nigeria](https://img.shields.io/badge/Country-Nigeria-green?style=for-the-badge&logoColor=white)

<div align="center">
  <img src="images/nigeria_youtube_thumbnail.jpg" width="100%"/>
</div>
<br>

## 📊 Project Overview
This project performs in-depth **Exploratory Data Analysis (EDA)** on YouTube's trending videos in **Nigeria**, revealing powerful insights into content consumption patterns, top creators, music dominance, comedy trends, and engagement drivers in one of Africa's largest digital markets.

**Dataset**: Real YouTube trending data scraped daily in Nigeria (2023–2025)  
**Source**: Kaggle / Public YouTube Trending Datasets (Region: NG)

## 🔥 Key Insights Discovered
- **Music dominates** – Over 65% of trending videos are Music (Afrobeats, Hip-hop, Gospel)
- Top Nigerian artists (Burna Boy, Davido, Wizkid, Asake) consistently dominate
- Comedy skits by Marlian & Instagram comedians have explosive growth
- Videos published between **6–9 PM WAT** get maximum traction
- Strong positive correlation: Views ↔ Likes (0.89), Views ↔ Comment Count (0.81)
- Average time to trend: ~18 hours after publish

## 📁 Project Structure
## 🛠️ Tools & Libraries
- Python 3.9+
- Pandas, NumPy
- Matplotlib, Seaborn
- WordCloud (for title analysis)
- Plotly (interactive charts)
- Jupyter Notebook

## 📈 Sample Visualizations
<div align="center">
  <img src="images/top_categories_nigeria.png" width="700"/>
  <br><br>
  <img src="images/top_channels...
  <img src="images/publish_time_heatmap.png" width="700"/>
  <br><br>
  <img src="images/views_vs_likes_scatter.png" width="700"/>
</div>

## 🚀 How to Run the Project
```bash
git clone https://github.com/YOUR-USERNAME/YouTube-Trending-Videos-Nigeria.git
cd YouTube-Trending-Videos-Nigeria
pip install -r requirements.txt
jupyter notebook notebooks/YouTube_Trending_Nigeria_Analysis.ipynb
