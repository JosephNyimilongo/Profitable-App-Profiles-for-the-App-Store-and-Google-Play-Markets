# App Market Data Analysis

This project analyzes mobile app data from the **Google Play Store** and the **Apple App Store** to identify what types of apps are more likely to attract users. Since our company develops **free apps monetized with in-app ads**, user growth is directly tied to revenue. The goal of this project is to guide developers toward creating apps that can reach a larger audience.  

## Project Overview

- Cleaned and prepared raw datasets (removed duplicates, handled missing data).  
- Analyzed app categories, ratings, reviews, and installs.  
- Compared the app markets on **Google Play** vs. **App Store**.  
- Determined which categories are most promising for growth.  

This project was built as a **portfolio-ready analysis** and showcases how Python fundamentals can be combined into practical, real-world data analysis.  

## Technologies Used

- **Python 3**  
- **Jupyter Notebook**  
- Libraries:  
  - `csv` (data loading)  
  - built-in Python tools (lists, loops, conditionals, dictionaries, functions)  

## Key Steps

1. **Data Cleaning**  
   - Removed incorrect and incomplete rows.  
   - Identified and removed duplicate apps (kept entries with the highest number of reviews).  

2. **Exploratory Data Analysis**  
   - Built frequency tables to understand app categories.  
   - Computed averages for installs and ratings.  
   - Compared Android and iOS markets.  

3. **Insights**  
   - Certain categories attract significantly more users.  
   - Free apps with large install bases offer the most advertising potential.  

## How to Run

1. Clone this repository:  
   ```bash
   git clone https://github.com/your-username/app-market-analysis.git
   ```  
2. Open the Jupyter Notebook:  
   ```bash
   jupyter notebook Basics.ipynb
   ```  
3. Run all cells to reproduce the analysis.  

## Results

- Final cleaned dataset sizes:  
  - Google Play: **9,659 apps**  
  - App Store: **7,197 apps**  
- Identified app categories with the highest user potential.  
- Clearer understanding of the mobile market landscape for ad-based apps.  

## Future Work

- Deeper visualization with `matplotlib` or `seaborn`.  
- Apply statistical tests to validate category popularity.  
- Extend analysis to include **app ratings over time**.  

## License

This project is for educational purposes and part of a guided portfolio project.  
