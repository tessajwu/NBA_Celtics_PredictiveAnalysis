# NBA_Celtics_PredictiveAnalysis

**Presentation Link:** https://www.canva.com/design/DAFhJV4Zn1M/RRUcQGTHGFD6BpU4Liqzyw/edit?utm_content=DAFhJV4Zn1M&utm_campaign=designshare&utm_medium=link2&utm_source=sharebutton
## Project Overview:

By exploring historical game data from Boston Celctics, this project aims to identify key determinants that could potentially explain the team's recent success. By providing a comprehensive and objective analysis of how each of those factors play into their outcomes for each game, the team can leverage that information to further optimize their success. Such information can also extend to sports betting where individuals are able to make more informed decisions. Overall, such analysis provide a better understanding of how predictive analysis can help transform the sports industry.


## Steps Taken:

1. **Data Acquisition:** Extracted 2 datasets from Basketball-Reference.com one consisting of every NBA game’s box score (i.e. points, steals, fouls, etc.) and the other containing records of all historical NBA team’s Elo ratings and RAPTOR ratings.
2. **Data Preprocessing:** Webscrapped data to create a singular merged dataset containing records representing a single game played in the regular season by the Boston Celtics starting from the 2018-2019 NBA season to the 2021-2022 NBA season. This is followed my data cleaning and feature selection to create dummy variablles and remove certain variables with no predictive power. Performed PCA to reduce multicollinearity, which can also help with over-fitting.
3. **Data Visualization:** Utilized Python data visualization libraries that created any findings that help better understand our predictive analysis. 
4. **Modeling:** Employed several Machine Learning algorithms (Decision Trees, Random Forest, k-NN, Logistic Regression) to identify key performance factors for a competitive edge, achieving an 82% model accuracy.


