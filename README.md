# Data Science Capstone
Final project for the IBM Data Science Professional Course - an introductory course to Data Science

```
Winning Space Race with Data Science .pptx
```

## Introduction

SpaceX is arguably the leaders of commercial space flight.
Their test launches save a lot of money through the retrieval of the first stage of a rocket.
SpaceY would like to investigate what variables of a rocket launch allow for a successful retrieval of the first stage.

## Data Collection

Using Python's Request library, the data on SpaceX's Falcon 9 launches was retrieved via the SpaceX Rest API endpoint.
Web-scraping using BeautifulSoup was also used to get data from the wikipedia pages of the launches.
```
Data Collection API.ipynb
Data Collection with Web Scraping.ipynb
```

## Data Wrangling

Pandas enabled the data wrangling. Each launch had its own outcome class set (1 for success, 0 for failure).
```
Data Wrangling.ipynb
```

## EDA

Using Matplotlib, Plotly and Seaborn, I was able to visualise the data for some exploratory data analysis.
This is where I asked the questions:
- Does payload mass affect the success outcome of the landings?
- Which launch site boasts the most successful landings?
- Which orbits have a higher landing success rate?
- Are SpaceX having more success with time?

Although visualising the data helped with initial analysis, I also performed some SQL analysis to gain more insight.
```
EDA with Visualization.ipynb
EDA with SQL.ipynb
```

## Interactive Data Visualisation

I wanted to visualise the number of launches per launch site on an actual map so I used Folium to accomplish this.
```
Interactive Visual Analytics with Folium.ipynb
```

## Predictive Analysis

Used 4 different Machine Learning models via Scikit-learn - Logistic Regression, Support Vector Machine, Decision Tree and KNN.
The models were trained and tested using train-test split data from the Data Collection.
I evaluated the accuracy test scores of each model and they were ready for SpaceY to use for predictions.