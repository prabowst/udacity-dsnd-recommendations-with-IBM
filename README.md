## Udacity Recommendations with IBM

This project entails the deliverables for Udacity Data Science Nanodegree Program: Recommendations with IBM

### Table of Contents

1. [Requirements](#requirements)
2. [Project Description](#description)
3. [Files](#files)
4. [Results - Blog Post](#results)
5. [Licensing and Acknowledgements](#licensing)

### Requirements<a name="requirements"></a>

The code runs using Python version 3. Several packages include pandas, numpy, matplotlib, seaborn, and pickle. 

### Project Description<a name="description"></a>

The project requires the student to work on the following tasks:

1. Exploratory Data Analysis: exploring the data prior to making recommendations, e.g. by visualizations.
2. Rank Based Recommendations: finding the most popular articles based on number of interactions (across all genre/types)
3. User-User Based Collaborative Filtering: look at users who are similar in terms of articles that they were interacting with in order to build a better recommendation for the users of IBM's platform.
4. Matrix Factorization: building a matrix decomposition (numpy's SVD) to predict new articles for an individual to interact with. 

### Files<a name="files"></a>

The files are organized as follows.
```
- data
| - articles_community.csv
| - user-item-interaction.csv  
- Recommendations_with_IBM.html 
- Recommendations_with_IBM.ipynb
- project_tests.py
- top_10.p
- top_20.p
- top_5.p
- README.md
```

### Results - Blog Post<a name="results"></a>

The overall results of the machine learning approach to build recommendations can definitely be improved. The further details of the result and potential methods to make the system better is presented within the .html and .ipynb files.

### Licensing and Acknowledgements<a name="licensing"></a>

Credit to Udacity course for the project template and IBM for the datasets.
