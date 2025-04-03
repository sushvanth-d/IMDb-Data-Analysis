# 🎬 IMDb Data Analysis Using Power BI

&nbsp;
## Project Overview

This report analyzes IMDb movie data, providing insights into revenue trends, genres, ratings, and country-wise performance. The goal is to explore industry patterns while improving proficiency in Power BI dashboards, DAX calculations, and data modeling.    

&nbsp;
## 📂 Dataset Details

_(Covers movies from the 1900s to mid-2023)_
- **source**: [IMDb Dataset](https://drive.google.com/file/d/1veOTyEq1Tf1Eha25tQojmP6sZnL9P5bq/view?usp=drive_link)
- **Columns Included** :
    - **Movie Title** - Name of the movie
    - **Genre** - Associated movie genre
    -  **Language** - Primary language of the movie
    -  **Score** - Viewer rating on a scale of 1-100
    -  **Release Date** - Year the movie was released
    -  **Budget** - Production budget (in USD)
    -  **Revenue** - Box office earnings (in USD)
    -  **Country** - Country where movie was produced

&nbsp;
&nbsp;
## Process
1. Data Collection <br />
       -IMDb dataset was sourced with various attributes like budget, revenue, and score.  
&nbsp;
2. Data Cleaning & Transformation <br />
       -Removed duplicate and missing values. <br />
       -Standardized formats for dates, currencies, and numeric values. <br />
       -Split multiple genres and then unpivoted them in separate table with the movie id for better analysis. <br />
&nbsp;
3. Data Modeling <br />
      -Created relationships between Movies, Genres, and Countries tables. <br />
      -Applied cross-filtering to enhance interactive insights. <br />
&nbsp;
4. Visualization & Analysis <br />
     -Built interactive Power BI dashboards for trend analysis. <br />
     -Identified key trends in revenue, production, budget, and profitability. <br />
&nbsp;

&nbsp;
   
## 📊 Key Visualizations & Insights
### Movies Production Trends
- **Chart Type** : Filled Map & Line Chart
- **Filled Map** - Number of Movies by Country
- **Line Chart** - Number of Movies by Year
- **Insight** - Australia, The United States, and Japan are the top movie-producing countries according to data. Movie production has seen significant growth over the years, with a peak in recent decades.

&nbsp;
![Screenshot (284)](https://github.com/user-attachments/assets/3213bb60-32f0-4732-9acc-836fddbd80ac)

&nbsp;
![Screenshot (285)](https://github.com/user-attachments/assets/ae67a293-1b59-4cc7-b509-f65fbfb41652)
&nbsp;

&nbsp;
### Movies by Genre 
- **Chart Type** : Tree Map
- **Insight** - Drama, Comedy and Action are the most commonly produced genres, while niche genres like Documentary and Musical have fewer releases.

&nbsp;
![Screenshot (286)](https://github.com/user-attachments/assets/f8a2fb8f-e438-454a-97a4-859544387cb0)

&nbsp;
&nbsp;
### Revenue vs Budget Analysis
- **Chart Type**: Scatter Chart
- **X-Axis** -Budget
- **Y-Axis** - Revenue
- **Legend** - Genre & Average IMDb Score
- **Insight** - High-budget movies generally earn more, but some low-budget films achieve unexpectedly high revenues, particularly in genres like horror and indie films.

  &nbsp;
![Screenshot (289)](https://github.com/user-attachments/assets/556d0b3d-6841-4f54-9dbd-d7148ede409e)
&nbsp;

&nbsp;
### Top 10 Highest Grossing Movies
- **Chart Type**: Clustered Column Chart
- **Insight** - The highest-grossing movies tend to be franchise films and blockbuster releases, which have significant budgets but also generate high profits. Movies like Avatar, Avengers: Endgame, and Titanic dominate the list, showing the financial success of large-scale productions.

&nbsp;
![Screenshot (290)](https://github.com/user-attachments/assets/821a37b1-d7ff-4f43-abf2-7652e7065ac2)
&nbsp;

&nbsp;
### Top 10 Revenue Generating Countries
- **Chart Type**: Stacked Column Chart
- **Insight** - Australia and the United States generate the highest box office revenues, followed by Japan and South Korea. Hollywood remains dominant, but other countries also contribute significantly to the global market.

&nbsp;
![Screenshot (291)](https://github.com/user-attachments/assets/9b86e1ab-a783-411d-9b03-d753c01be7ba)
&nbsp;

&nbsp;
### Budget vs Profit Trends Over Time
- **Chart Type**: Line Chart
- **X-Axis** - Year
- **Y-Axis 1** - Budget
- **Y-Axis 2** - Profit
- **Insight** - The post-2000 period saw increasing budgets, aligning with industry growth and the expansion of high-budget franchises.In 2020, both budget and profitability spiked, showing a surge in investment and returns. However, by 2022, budget and profitability became close, indicating a shift in spending and earnings trends.

&nbsp;
  ![Screenshot (292)](https://github.com/user-attachments/assets/d520ae2a-d0f4-489a-a156-ac56b043fff4)

&nbsp;
&nbsp;

&nbsp;
## 📌 Key Takeaways

- "Avatar" remains the highest-grossing movie, followed by "Avengers: Endgame," with most top 10 movies generating over 1.5 billion dollars in revenue.
- The United States and Australia generate the highest revenue in the film industry.
- Movie production has grown rapidly, especially after 2000, with the rise of streaming platforms and digital distribution.
- Higher budgets generally lead to higher profits, but some lower-budget films also achieve significant profitability.
- In 2020, budget and profit spiked, but by 2022, they became close, suggesting a shift in movie industry dynamics.

&nbsp;
&nbsp;
## 📸 Dashboard Previews
&nbsp;

![Screenshot (293)](https://github.com/user-attachments/assets/9fd1beb4-14cc-4720-bbee-c2e4e747c756)
&nbsp;

![Screenshot (294)](https://github.com/user-attachments/assets/d6cdd2c6-76e2-4303-98ac-374edd5815b2)
&nbsp;

![Screenshot (295)](https://github.com/user-attachments/assets/893000b6-30c1-4a7d-97c0-600b97c3e5b2)
&nbsp;


&nbsp;
## 📢 Conclusion
The analysis provides insights into the evolution of the film industry, the impact of high-budget movies, and the revenue contribution of different countries. Power BI was instrumental in creating an interactive and visually engaging report to identify key trends.

&nbsp;
&nbsp;
##
📌 Author: Sushvanth Dudgundi     
📅 Project Date: 2025    
📁 Report Type: Interactive Power BI Dashboard

&nbsp;
🚀 Download the full Power BI report for an in-depth, interactive experience! [IMDb Data Analysis Report](https://github.com/sushvanth-d/IMDb-Data-Analysis/blob/main/IMDB%20Data%20Analysis%20Project%20By%20Sushvanth_D.pbix)


