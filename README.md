# 📊 Netflix Data Analysis Project
# Problem Statement:
Analyze the Netflix content dataset (netflix1.csv) by performing data cleaning, preparation, and exploratory data analysis to uncover trends in content types, content growth over time, ratings distribution, and the most common genres, countries, and directors. The project concludes with insights into Netflix’s overall content strategy. 

# Prerequisites:
Before running this project, make sure you have:

*Python 3.7+
*Jupyter Notebook / Google Colab / VS Code
*Basic understanding of:
*Python
*Data Analysis
*Pandas & Data Visualization

# 📚 Libraries Used

*pandas:	Data loading, cleaning, manipulation
*numpy:	Numerical operations
*matplotlib.pyplot:	Creating plots (line chart, pie chart)
*seaborn:	Advanced visualizations (count plots, bar charts)

These libraries are imported and used throughout the analysis. 

# 🔎 Analysis Workflow

# Data Loading: 
       Loaded dataset using pandas.read_csv().

# Date Processing:
       Converted date_added to datetime format.
       Extracted year_added for trend analysis.

# Data Cleaning:
       Checked missing values.
       Removed duplicate records.
    Split duration into:
      duration_value (numeric)
      duration_unit (min / Season)

# Content Type Distribution:
      Compared Movies vs TV Shows.
      Visualized using pie chart.

# Temporal Trends:
      Analyzed how content additions changed by year.
      Visualized using line plot.

# Ratings Analysis:
      Studied overall ratings distribution.
      Compared ratings across Movies and TV Shows.

# Top Categories Analysis:
    Identified: Top 10 Genres, Countries, Directors, Visualized using bar plots.

# Final Insights:
    *Movies dominate Netflix’s catalog.
    *Mature ratings (TV-MA, TV-14) are most common.
    *US, India, and UK produce the most content.
    *International Movies and Dramas are top genres. 

# 📈 Key Takeaways:

*Strong growth in content additions over recent years

*Netflix focuses more on Movies than TV Shows

*Global expansion is evident (high international content)

*Popular genres lean towards Drama and International content
