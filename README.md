# Tactical-Mapping-Passing-Lane-Intelligence
Goal: Discover tactical structures and visualise where teams create space and passing opportunities.

Build plan
1. Extract pass locations, receivers, possessions, and player positions.
2. Plot passing networks and average player locations.
3. Generate player heatmaps and ball progression maps.
4. Apply clustering to identify recurring passing patterns.
5. Mine association rules to identify frequent pass combinations.
6. Build an expected threat (xT) model for ball progression.
7. Add passing-lane and pitch-control estimates if tracking data is available.
Suggested stack: Python, NetworkX, mplsoccer, scikit-learn, Plotly.

Module practice: Clustering, association rules, data mining, feature engineering.

Evaluation: Pattern stability, pass-prediction accuracy, and xT usefulness on held-out matches.

Extension: A tactical comparison tool that highlights how a team's structure changes when specific players are substituted.

Data caveat: Event data supports passing networks and xT; credible pitch-control calculations generally require tracking data.
