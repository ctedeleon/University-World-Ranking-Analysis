# University-World-Ranking-Analysis 
![alt text](https://us.123rf.com/450wm/jemastock/jemastock1906/jemastock190659336/125401673-back-to-school-education-backpack-and-books-with-pencils-in-cup-and-world-globe-cartoons-vector.jpg?ver=6)

Final analysis project for the Data Immersion Achievement for the Career Foundry Data Analytics course

### Project Goals
This analysis project focused on comparing three distinguished university world ranking systems and determining if specific factors can be used for estimating the world rank of a university. 

### Data Sources
Three university world ranking systems were used: Center for World University Rankings (CWUR), the Academic Ranking of World Universities (ARWU), and the Times Higher Education (THE). These data sets were downloaded from Kaggle (https://www.kaggle.com/datasets/mylesoneill/world-university-rankings). Each ranking systems utilizes different variables or factors for determining a university's status. Some examples of factors include: quality of faculty, research output, number of publications, teaching score, alumni employment, number of citations, and quality of education. A geojson file was used to incorporate a geographical component for spatial analysis. The file was obtained from https://datahub.io/core/geo-countries#resource-countries. 

### Workflow 
1. Exploratory Data Analysis 
    - Explore relationships between variables in each data set
    - Correlation heatmaps and coefficients 
    - Scatterplots 
    - Form hypotheses 
    - Determine key questions 
2. Hypothesis Testing 
    - Determine the type of analysis that best describes the data 
    - Regression Analysis (slope, R2 score, mean squared error)
    - Cluster Analysis 
    - Time Series Analysis 

### Hypotheses 
*Quality of Faculty*
 - Ho: If the quality of faculty value is high, then the university score will also be high, resulting in a top world rank. 
 - Ha: If the quality of faculty value is high, then the university score will be low, resulting in a low world rank. 

*Research Output*
 - Ho: If the university has a high research output, then the university score will also be high, resulting in a top world rank. 
 - Ha: If the university has a high research output, then the university score will be low, resulting in a low world rank. 

### Key Questions
1. Are the top 10 universities the same for each ranking system? 
2. Do all ranking systems include the same countries? 
3. How does the university score change over time? 

### Scripts 
Only some scripts were uploaded onto GitHub (due to size issues). The scripts included discuss cleaning the data sets (i.e. checking for data types, missing values, and duplicates), supervised machine learning (regression analysis), unsupervised machine learning (cluster analysis), and spatial analysis (choropleth maps for the ARWU and Times data sets only). 

### Link to Tableau Storyboard
https://public.tableau.com/app/profile/christina.deleon/viz/6_7WorldRankingofUniversities/WorldRankingofUniversities?publish=yes
