# IMDB Data Analysis

This project performs exploratory data analysis (EDA) on an IMDB dataset to uncover insights about genres, countries, and movie durations.  
The workflow focuses on data cleaning, visualization, and identifying outliers.

## Tools & Libraries
- **Python**
- **Pandas** – data cleaning and manipulation
- **Seaborn** – statistical data visualization
- **Matplotlib** – plotting and figure customization

## Data Preparation
- Loaded the IMDB dataset
- Dropped unnecessary columns
- Removed duplicate records to ensure data quality
- Verified the cleaned dataframe structure

## Analysis Performed

### Genre Analysis
- Analyzed the distribution of movie genres
- Identified the **top 10 most common genres**
- Visualized genre distributions using **Seaborn count plots**
- Applied the **rocket color palette** for consistent styling

### Country Analysis
- Examined the distribution of movie production countries
- Identified the **top 10 countries**
- Visualized country distributions using bar plots

### Duration & Outlier Analysis
- Analyzed movie duration values
- Detected outliers using statistical methods
- Visualized duration outliers with a **box plot**
- Displayed:
  - Dataset **with outliers**
  - Dataset **after removing outliers**

## Visualizations
- Genre distribution plots
- Top 10 genres visualization
- Country distribution plots
- Box plot for movie duration outliers

## How to Run
1. Clone the repository
2. Ensure the IMDB dataset file is available in the project directory
3. Open `IMDB.ipynb`
4. Run all cells sequentially

## Notes
This project focuses on exploratory analysis and visualization.  
No predictive modeling or machine learning techniques are applied.
