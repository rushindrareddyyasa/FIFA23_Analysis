# FIFA 23 Player Data Analysis & Power BI Dashboard

This project showcases end-to-end analysis of the FIFA 23 player dataset using Python for preprocessing and Power BI for visualization. The notebook walks through data cleaning and transformation, while the dashboard highlights key insights into player performance, value, and demographics.

## 📁 Files Included

- `FIFA23_official_data.csv`: The original FIFA 23 dataset used for analysis.
- `analysis.ipynb`: Python notebook used for data cleaning and feature engineering.
- `dashboard.mp4`: A short demo video of the interactive dashboard (to be added).
  
## 🔍 Key Highlights from the Notebook

- Removed non-essential columns like `Photo`, `Flag`, and `Loaned From`
- Transformed string monetary columns (`Wage`, `Value`, `Release Clause`) into numeric values
- Extracted insights from:
  - Age, Wage, Value, Overall, Potential, Position, Nationality, and more
- Created a cleaned dataset: `processed_fifa.csv` for Power BI

## 📊 Dashboard KPIs & Visuals

- **KPIs**:
  - Total Players
  - Highest Overall Rating
  - Highest Potential
- **Visuals**:
  - **Pie Chart**: Distribution by Preferred Foot (Left vs Right)
  - **Donut Chart**: Age Group Segmentation
  - **Bar Charts**:
    - Top 10 Players by Value
    - Top 10 Clubs by Average Value
  - **Scatter Plot**: Wage (€) vs Value (€)

## 🛠 Tools Used

- Python (Pandas, Matplotlib, Seaborn)
- Power BI for dashboard design
- Jupyter Notebook for processing

## 📽 Demo

Dashboard video demo will be shared here and on LinkedIn.

## 🚀 How to Use

1. Open [analysis.ipynb](./FIFA 23 Cleaned) to understand the data preparation.
2. Use `FIFA 23 Cleaned.csv` in Power BI to build your own dashboard or explore the existing one.
3. Explore the dashboard or use `FIFA23_official_data.csv` to experiment with your own cleaning logic.
4. View the dashboard via the image or demo video.

---

⭐ Star this repo if it inspired your own data project!
