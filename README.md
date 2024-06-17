# README for nd025-Data-Scientist-Blog-Post
Deliverable for the Udacity nano degree program Data Scientist (nd025):  Writing a Data Scientist Blog Post

## Biopic Movies Analysis
This repository contains the analysis of biopic movies from a IMDb database extract, focusing on various aspects such as the distribution over the years, gender diversity, frequent actors, common attributes of biopic subjects, movie ratings, and box office revenue. Additionally, the repository explores the challenges faced in predicting movie ratings using machine learning due to skewed feature distributions and correlated features.

## Table of Contents
- [Introduction](#introduction)
- [Dataset](#dataset)
- [Analysis Questions](#analysis-questions)
- [Findings](#findings)

## Introduction
Biopic movies are a popular genre that dramatizes the lives of real people. This analysis aims to uncover patterns and insights from biopic movies. The repository also addresses the limitations and challenges in predicting movie ratings using machine learning.

## Dataset
`biopics.csv` contains the following variables:

Variable | Definition
---|---------
`title` | Title of the film.
`site` | URL from IMDB.
`country` | Country of origin.
`year_released` | Year of release.
`box_office` | Gross earnings at U.S. box office.
`director` | Director of film.
`number_of_subjects` | The number of subjects featured in the film.
`subject` | The actual name of the featured subject.
`type_of_subject` | The occupation of subject or reason for recognition.
`race_known` | Indicates whether the subject’s race was discernible based on background of self, parent, or grandparent.
`subject_race` | Race of the subject.
`person_of_color` | Dummy variable that indicates person of color.
`subject_sex` | Sex of subject.
`lead_actor_actress` | The actor or actress who played the subject.

`biopics_with_ratings.xlsx` contains the same data as `biopics.csv` with the addition of movie rating.

Variable | Definition
---|---------
`rating` | IMDb rating of the film.

Source: [IMDb](http://www.imdb.com/).

## Analysis Questions
The following questions were investigated in the analysis:
1. What is the distribution of biopic movies over the years and the gender diversity in the biopics subjects?
2. Who are the most frequent actors playing in biopics and which type of subject do they play?
3. What are the most common attributes (sex, race, profession) of the biopic subjects?
4. Which biopic movies received the highest ratings and is there a correlation with its box office revenue?
5. Can we predict the rating of a biopic movie based on some of its features using machine learning?

## Findings
#### 1. Distribution of Biopic Movies Over the Years and Gender Diversity
- Biopic movies have fluctuated over the years with notable increases since the 90's.
- There is a significant gender imbalance in biopic subjects, with a predominance of male subjects.

#### 2. Frequent Actors in Biopics and Types of Subjects
- Certain actors frequently appear in biopics, also with a predominance of male actors.

#### 3. Common Attributes of Biopic Subjects
- The most common attributes of biopic subjects include being male, white, and with occupations like crime, politics, music, and sports.

#### 4. Highest Rated Biopic Movies and Correlation with Box Office Revenue
- Highest-rated biopic movies often achieve significant box office success.
- There is a positive correlation between movie ratings and box office revenue.

#### 5. Predicting Movie Ratings Using Machine Learning
- Skewed feature distributions and correlated features present challenges for prediction.
- Bias towards dominant values and multicollinearity impact model performance and reliability.

---

For more details on the analysis and to view the visualizations, please refer to the Jupyter notebook in this repository.
