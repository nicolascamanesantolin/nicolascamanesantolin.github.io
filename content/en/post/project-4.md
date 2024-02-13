---
date: 2023-06-23T10:58:08-04:00
featured_image: "/images/futbol.jpg"
title: "Project 4: Statistical analysis of the five major European football leagues"
---

This is the project carried out for my final degree project for the Computational Mathematics degree at Jaime I University.

The project is based on the use of different data mining techniques, including principal component analysis to reduce the dimension of a data set, hypothesis testing to evaluate data, logistic regression to predict the occurrence of a binary event, and ordinal regression to predict categorical variables. The purpose of employing these techniques is to study data on various European football leagues. In addition to implementing and describing the techniques used, the document explains the theoretical foundations of these procedures. The results obtained from the implementation of these procedures are also presented. The project's development is divided into three phases.

In the first phase, the existence of differences between teams based on their position in the standings is explored. To do this, the Kruskal-Wallis test is initially used to assess whether differences can be found among teams within the same league and among different leagues. If differences are found, the Tukey post hoc test is employed to regroup these teams. Additionally, in this phase, correlation maps and PCA techniques are used to identify hidden patterns in the data and visualize teams through dimensionality reduction.

In the second phase, the goal is to identify quantifiable indicators of a team's play during the season in any of the five leagues that are related to playing style and are crucial for the team's qualification for European competitions. As part of this phase, correlation maps and a two-dimensional graph resulting from applying the PCA algorithm with the variables from this section are generated. Different implementations of a logistic regression algorithm are carried out to analyze the resulting odds ratio graphs.

Finally, in the third phase, an ordinal regression model is implemented. In this case, the target variable is a categorical variable with three possible values: Europe, Permanence, and Descent. It depends on whether, at the end of each recorded season, the team qualified for one of the two European competitions (Champions League and Europa League), finished in the mid-table zone, or ended up in the relegation zone of their respective league.

[Link to GitHub Repository](https://github.com/nicolascamanesantolin/TFG.git)