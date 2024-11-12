# Netflix Movies and TV Shows Clustering
<p align="center">
  <img src="https://github.com/Girish-Parashar/Netflix-Movies-and-TV-Shows-Clustering-Capstone/blob/main/Leonardo_Phoenix_Design_a_professional_project_poster_for_Netf_0.jpg" width="500"/>
</p>


## Project Summary
This dataset includes TV episodes and movies accessible on Netflix as of 2019. The dataset is sourced from Flixable, a third-party Netflix search engine. In 2018, they published an interesting research revealing that the quantity of TV series on Netflix has nearly tripled since 2010. Since 2010, the number of movies available on the streaming service has declined by almost 2,000, but the number of TV series has nearly tripled. It will be interesting to see what additional insights can be extracted from the same dataset. Integrating this dataset with additional external datasets, such as IMDB ratings and Rotten Tomatoes, can yield numerous intriguing results.

In this project, we were needed to:

- **Exploratory data analysis**: Understanding what kind of information is available in different countries. In recent years, Netflix has shifted its attention from movies to television shows.
- **Text-based feature matching**: Using clustering to group related content. The goal is to evaluate and cluster a dataset related to Netflix.
- The dataset contains various properties related to Netflix episodes and movies, including title, genre, release year, runtime, rating, and others.
- **Clustering**: Using unsupervised machine learning algorithms such as **K-Means** and **Hierarchical Clustering** to identify patterns and similarities in the content available on the platform.
- **Evaluation**: Using the elbow method to determine the ideal number of clusters.
- **Insights**: Analysis will help Netflix with content categorization, recommendation algorithms, and content purchase methods.
- **Visualizations**: Presenting results with clear charts and graphs.

## Problem Statement
This dataset, obtained from Flixable, includes Netflix's TV series and movies available as of 2019. Flixable, an external Netflix search engine, acts as the source.

In 2018, an intriguing analysis revealed a substantial spike in Netflix's TV show count, which has nearly tripled since 2010. In contrast, the number of movie titles decreased by over 2,000. Uncovering additional insights from this dataset promises to be an engaging exploration.

Netflix, a global streaming behemoth, has a huge collection. Nonetheless, users struggle with content finding amidst the numerous options.

To solve this, we use **unsupervised learning** to cluster Netflix's films and TV programs. We hope to improve content suggestions by employing clustering algorithms such as **K-Means** or **Hierarchical clustering**, allowing consumers to receive tailored recommendations.

This project entails evaluating a dataset of Netflix titles, which includes genre, release year, actors, and plot descriptions. The goal is to discover clusters based on shared characteristics in order to improve the categorization of films and television programs.

The ultimate goal is to create an accurate clustering model to help with Netflix's content recommendation and discovery. This concept has the potential to transform the user experience or contribute to Netflix's content algorithm improvements.

## General Guidelines:
- Well-structured, formatted, and commented code is required.
- **Exception Handling**, **Production Grade Code** & **Deployment Ready Code** will be a plus. Those students will be awarded some additional credits.
- **Deployment Ready Code** is defined as: The whole `.ipynb` notebook should be executable in one go without a single error logged.
- Each and every logic should have proper comments.
- You may add as many charts as you want. Ensure that for each chart, the following format is answered:
  - **Why did you pick the specific chart?**
  - **What is/are the insight(s) found from the chart?**
  - **Will the gained insights help in creating a positive business impact?** Are there any insights that lead to negative growth? Justify with a specific reason.

## Attributes in the Dataset:
1. **show_id**: Unique ID for every Movie / TV Show
2. **type**: Identifier - A Movie or TV Show
3. **title**: Title of the Movie / TV Show
4. **director**: Director of the Movie
5. **cast**: Actors involved in the movie/show
6. **country**: Country where the movie/show was produced
7. **date_added**: Date it was added to Netflix
8. **release_year**: Actual Release year of the movie/show
9. **rating**: TV Rating of the movie/show
10. **duration**: Total Duration - in minutes or number of seasons
11. **listed_in**: Genre
12. **description**: Summary description

## Steps Involved in the Project:
1. **Data Preprocessing**:
   - Handle missing values
   - Remove extraneous columns
   - Convert categorical variables to numerical representations

2. **Exploratory Data Analysis (EDA)**:
   - Visualizations and statistical summaries
   - Understanding the distribution of variables, trends, and correlations

3. **Clustering Algorithms**:
   - Apply **K-Means**, **Hierarchical Clustering**, and other algorithms
   - Use the elbow method for determining the optimal number of clusters
   - Profile clusters and identify key patterns

4. **Evaluation**:
   - Assess and interpret the clusters
   - Provide recommendations for content categorization and content recommendation

5. **Visualizations**:
   - Charts and graphs summarizing findings
   - Insights for Netflix’s content purchase and recommendation systems

## GitHub Link:
[Netflix Movies and TV Shows Clustering Capstone](https://github.com/Girish091998/Netflix-Movies-and-TV-Shows-Clustering-Capstone)
