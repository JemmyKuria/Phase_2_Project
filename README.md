# PHASE_2_PROJECT

# PROJECT OVERVIEW
**Goal:**  
Identify the types of films performing best in the box office and understand the factors influencing their success.

**Analysis:**  
Used Python to merge and clean multiple movie datasets, calculate profit and ROI, and run visualisations and statistical tests to uncover what drives box office success.

**Deliverable:**  
Provide insights on the most profitable genres, budgets, and release timings to guide future video content production and help producers make data-driven decisions for maximising box office returns.

# BUSINESS UNDERSTANDING
**Business Goal:**  
Identify which types of films perform best across key performance metrics — such as ratings, popularity, and return on investment (ROI)

**Stakeholders:**  
1. Executive Leadership: Responsible for strategic decision-making and resource allocation  
2. Marketing Team: Needs insights on audience preferences to shape promotional campaigns  
3. Production Team: Requires data on successful genres and budgets for content planning  
4. Finance Team: Focused on understanding ROI and budget optimisation  
5. Data Analysts: Conduct analysis and deliver insights to decision-makers  

**Key Questions:**  
- Which movie genres are the most popular among audiences?  
- Which months are the best for releasing movies to maximise performance?  
- What is the ideal budget range for a film to attract popularity or success?  
- Which genres yield the highest return on investment (ROI)?  

# OBJECTIVES
- Identify the most profitable movie genres based on ROI  
- Determine the best release months for high-performing films  
- Examine the impact of production budget on movie profitability  
- Recommend strategies for maximising ROI in future film productions  

# DATA UNDERSTANDING AND ANALYSIS

**Datasets Used:**  
- IMDb (SQL database): rating, genre, runtime  
- Box Office Mojo (CSV): domestic revenue and foreign revenue  
- The Numbers (CSV): production budget  
- The Movie DB (CSV): popularity score, release date  

**Challenges:**  
- Budget data was missing for some films  
- No universal movie ID across datasets  

**Data Cleaning:**  
- Used Box Office Mojo as the base dataset  
- Dropped rows with missing values (except for revenue columns, where nulls were set to 0)  
- Standardised movie titles for consistency  
- Merged datasets and removed duplicates  
- Engineered new features: Total Gross, ROI, Profit, Release Month  

# ANALYSIS

## Movie Popularity by Genre
Adventure, Action, and Sci-Fi emerged as the most popular genres.
![alt text](image-1.png)

## Average ROI by Genre
Horror, Mystery, and Thriller had the highest return on investment rates.
![alt text](image-9.png)

## Median ROI by Budget Group
Return on investment increased with larger budgets.
![alt text](image-7.png)

## Average Movie Popularity by Month
May, November, and July had the highest average viewership of movies.
![alt text](image-8.png)


## Hypothesis Testing
- **Null Hypothesis (H0):** Genre has no effect on the ROI of a movie  
- **Alternative Hypothesis (H1):** Genre has a significant effect on the ROI of a movie  
- **P-value:** 0.0000  
- **Conclusion:** There is strong statistical evidence that genre significantly affects ROI.

## Tableau Visualisation
https://public.tableau.com/app/profile/faith.githaiga/viz/BoxOffice_17460097972510/BoxOfficeInsights?publish=yes


# CONCLUSION
- Horror, Mystery, and Thriller movies had the highest ROI  
- Adventure, Action, and Sci-Fi were the most popular but not the most profitable  
- May, November, and July were the best months for high-performing releases  
- Higher budgets were generally linked to better ROI, but not always a guarantee  

# RECOMMENDATIONS
- **Genres for ROI:** Focus on Horror, Thriller, Mystery  
- **Genres for Popularity:** Consider Adventure, Action, Sci-Fi  
- **Best Months for Release:** May, July, November  
- **Budget Strategy:** Invest wisely—larger budgets can yield higher ROI with careful planning  

# NEXT STEPS
- Examine regional performance to guide targeted marketing  
- Build a predictive model to estimate ROI from budget, genre, and release date  
- Incorporate marketing spend data to evaluate its impact on success  

# TRELLO LINK
https://trello.com/b/qHiJCiSx/movie-analysis?utm_source=eval-email&utm_medium=email&utm_campaign=board-invite
