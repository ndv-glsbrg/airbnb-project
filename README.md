# Airbnb Data Analysis (NYC)

This project explores an Airbnb listings dataset (~30MB) for New York City using **Python** and **pandas** in Jupyter Notebook.  
The goal was to practice real-world data analysis and storytelling — not only through code, but also by preparing a presentation and dashboard.


## Project Context

This was a project focused mainly on **explaining insights and telling a story**.  
Some details were simplified or spoken rather than written, in order to keep the narrative clear for the audience.  
No essential information was missed — it was just delivered verbally during the presentation.  

The result was a **big success**:  
- The analysis and presentation was the only one that day to receive **only positive feedback**.  
- It was presented to **senior leadership and high-ranking professionals**.  
- It led directly to **job offers**.  
- It demonstrated the value of combining strong technical skills with clear communication and storytelling.  


## Key Questions Explored
- How do review categories (accuracy, cleanliness, communication, etc.) correlate with overall rating?  
- How is price distributed across listings? (split into 5% quantile groups)  
- What combinations receive the highest average ratings?  
- How do Superhosts compare to non-Superhosts?  


## Methods
- Data loaded and cleaned with **pandas**  
- Grouping and aggregation with `.groupby()`, `.agg()`, `.size()`, `.mean()`  
- Correlation analysis with `.corr()`  
- Quantile segmentation with `pd.qcut()`  
- Exploratory analysis in Jupyter Notebook (`exploration.ipynb`)  
- Visual storytelling through **PowerPoint** and **dashboard screenshots**  


## Example Insights
- Review metrics are highly correlated with overall ratings (>0.98).  
- Larger properties (e.g., 4 bed / 3 bath) tend to achieve the highest average ratings.  
- Superhosts represent a smaller share of listings but consistently perform better in reviews.  
- Price distribution is highly skewed, with most listings clustered in the lower quantiles.  


## Repository Structure
airbnb-project/
─ exploration.ipynb # Jupyter notebook with full analysis
─ nyc_listings_airbnb.pptx # Presentation slides
─ Interactive_dashboard_pic.png # Dashboard screenshot
─ requirements.txt # Python dependencies (pandas)
─ README.md # Project description (this file)
─ .gitignore # Excludes venv, data, checkpoints, etc.
