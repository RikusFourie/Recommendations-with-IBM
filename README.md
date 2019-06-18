# Recommendations-with-IBM

## Project Overview
For this project, I analyzed the interactions that users have with articles on the IBM Watson Studio platform and built a recommendation engine that could recommend articles that they might like. 

### Steps followed during the project:
1. Exploratory Data Analysis
Before making recommendations of any kind, I explored the data I worked with for the project. Dive in to see what you can find. I looked at the overall data structure and found some interesting information.

2. Rank Based Recommendations
To combat the cold start problem I build a rank based recommendation engine that will recommend articles based on checkouts.

3. User-User Based Collaborative Filtering
Here I build a recommendation engine that finds similar users and recommends articles based on similarity to other users.

4. Matrix Factorization
Finally, I completed a machine learning approach to building recommendations. Using the user-item interactions, I build out a matrix decomposition. Using my decomposition, I got an idea of how well I can predict new articles an individual might interact with (spoiler alert - it isn't great). I finally discussed which methods I might use moving forward, and how I might test how well your recommendations are working for engaging users.
