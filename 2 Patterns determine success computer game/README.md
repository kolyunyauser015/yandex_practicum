__Topic:__ Study of patterns that determine the success of games.

__Purpose:__ Identify patterns that determine the success of the game for choosing a potentially popular product and plan advertising campaigns. According to historical data on game sales, user and expert ratings, genres and platforms, it is necessary to prepare proposals for the store for the strategy next year.

__Stack:__
1. Open data files. Study general information and omissions.
2. Data preprocessing
- changed the name of columns (change to normal form-lowercase);
- removed gaps in the Name and Genre columns;
- in the Year_of_Release column, the omissions are replaced with the year of release of the game with the same name, the rest - with the year of release updated from other sources (Internet);
- omissions in the columns Critic_Score, User_Score are replaced with the median value of the corresponding group, but previously in the column User_Score tbd are replaced with -1 (when calculating the median, -1 values were not taken into account);
- changed data types;
- in the User_Score column, values lead to a 100-point scale.
3. A research analysis of the data was carried out.
- determined how many games were released in different years;
- analysis of changes in sales by platform was carried out;
- selected platforms with the highest total sales and studied the change by year;
- the period of "life" of platforms is defined;
- the current period of three years has been determined;
- it is determined which platforms are leading in sales, growing or falling. Several potentially profitable platforms have been selected;
- built charts for global game sales broken down by platform;
- an analysis of how users 'and critics' reviews affect sales within one popular platform. A scatter plot is constructed and the correlation between reviews and sales is calculated.
- an analysis of the distribution of games by genre was carried out.
4. A user profile of each region has been compiled. The most popular platforms and most popular genres are defined for the user of each region. The impact of the ESRB rating on sales in a particular region is determined.
5. Hypothesis testing:
Average user ratings for the Xbox One and PC platforms are the same;
The average user ratings for the Action and Sports genres are different.
6. General conclusion.

__Conclusion:__ The decline in sales of games with the Adventure genre suggests refraining from their release next year. But the release of programs with the Shooter, Platform genres needs to be increased. Hypothesis testing showed: The hypothesis that the average user ratings of the Xbox One and PC platforms are the same is rejected. The hypothesis that the average user ratings of the Action and Sports genres are different is not proven.

__Skills and tools:__ Python, Pandas, NumPy, Matplotlib, data preprocessing, research data analysis, descriptive statistics, testing statistical hypotheses.

__Project status:__ Completed.
