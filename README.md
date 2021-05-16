# IBM Watson Recommendation Engine
This project explores different approaches to building recommendation engines, in specific to recommend articles to 
users of the IBM Watson platform. The interactions between users and articles are analyzed to make recommendations 
about new articles that are most pertinent to a specific user.

The Jupyter notebook contains:
1. Exploratory Data Analysis
2. Rank Based Recommendations (i.e. most popular articles)
3. User-User Based Collaborative Filtering (i.e. finding similar users and articles they have interacted with)
4. Matrix Factorization (i.e. a machine learning approach to predict which articles a user might interact with)
plus discussions of alternative methods to move forward, and how to test the quality of the recommendations.
    
The project is part of the Udacity Nanodegree in Data Science to learn experimental design and train building 
recommendation engines.

![Screenshot](screenshot.png)

## Required Installations
Jupyter notebook, Python 3, Matplotlib, Numpy, Pandas.

## File Descriptions
The project consists of the following files:
```
Disaster_Response/  
│  
├── data/  
│   ├── articles_community.csv   # csv file containing information about articles  
│   ├── user-item-interactions.csv   # csv file containing user interactions  
│  
├── project_tests.py   # python file to run tests
├── Recommendations_with_IBM.html   # html file as output of Jupyter notebook
├── Recommendations_with_IBM.ipynb   # Jupyter notebook containing all analysis
├── top_5.p   # pickle file
├── top_10.p   # pickle file
├── top_20.p   # pickle file
├── user_item_matrix.p   # pickle file
│  
```

## Acknowledgements
Data was provided by IBM Watson as part of the Udacity Nanodegree in Data Science. Thanks IBM!



