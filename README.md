# NBA-Market-Analysis
Data science project exploring the relationship between NBA market size, spending, and team wins using regression and decision tree models in R

# 🏀 NBA Market Size vs. Team Wins  
*Exploring the relationship between big markets, spending, and NBA success*  

## 📌 Project Overview  
This project analyzes whether **NBA teams in larger markets** (wealthier owners, bigger cities, higher player salaries) perform better than small-market teams in terms of **wins**.  

Using multiple datasets (salaries, salary cap, owner net worth, city population, and team wins), we applied **statistical modeling** and **machine learning** to test whether market size really matters — or if other factors are more predictive of success.  

## ⚙️ Tools & Skills  
- **Language**: R  
- **Libraries**: tidyverse, caret, ggplot2, rpart  
- **Techniques**: Data Wrangling, Linear Regression, Regression Trees, Visualization, Model Evaluation  

## 🔍 Key Steps  
1. **Data Collection**: Gathered datasets on NBA salaries, owner net worth, salary caps, city population, and win totals.  
2. **Data Cleaning**: Merged and standardized datasets, handled missing values.  
3. **Exploratory Analysis**: Visualized correlations between market-related variables and wins.  
4. **Modeling**:  
   - **Linear Regression**: Tested predictive power of market size, spending, and other factors.  
   - **Regression Tree**: Built interpretable model to see decision splits (e.g., high salary cap spending vs. wins).  
5. **Evaluation**: Compared R² and interpretability of regression vs. tree models.  

## 📈 Results & Insights  
- **Market size (city population, owner net worth) had little effect on wins.**  
- **Spending relative to the salary cap was the strongest predictor** of team success.  
- Regression model (R² ~0.72) outperformed regression tree (R² ~0.55), but trees highlighted clear spending thresholds for competitive teams.  
- Takeaway: **It’s not how big your market is — it’s how much your organization invests.**  

## 📊 Example Visuals  
(Add screenshots of your regression plot, regression tree, or correlation heatmap here once you export them as PNGs.)  

## 🚀 Future Improvements  
- Add time-series analysis across multiple seasons.  
- Re-implement models in Python with Scikit-learn for portfolio variety.  
- Build an interactive dashboard (Shiny in R or Streamlit in Python).  

## 👤 Author  
**John Hankwitz** – Senior at UMass Amherst studying Informatics (Data Science concentration) & Computer Science minor.  
- [GitHub Profile](#)  
- [LinkedIn](#)  
