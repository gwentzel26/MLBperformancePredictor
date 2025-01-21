# **Linear Model Predicting MLB player WAR(Impact Score) for 2025 Season**
  
## **Description**

    I have created a linear model with 6 performance metrics as the predictor variables: 
    wRC+, Hard Hit %, BB/K, ISO, BsR, and Def to predict 2025 player impact using the previous 3 seasons. 
    The linear model underwent a Box Cox transformation, hypthosesis testing before Confidence and Prediction 
    Intervals were created.
      
## **Table of Contents** 
      
  - [Dataset](#dataset)
  - [Libraries](#libraries)
  - [Results](#results)
  - [Attachments and Contact](#attachments)
      
## **Dataset <a id="dataset"></a>**
  
    Source: fanGraphs.
    Content: Historical Performace Metrics of qualifying players from the 2022-24 Seasons.
    Variables: WAR, wRC+, Hard Hit %, BB/K, ISO, BsR, Def
    Format: CSV file
    
    Data file is attached in this repository

## **Libraries <a id="libraries"></a>**

    R: Primary programming language for the project.
    dplyr: Data manipulation and preprocessing.
    ggPlot2: Data visualization.
    corrplot: Correlation Plots.

## **Results <a id="results"></a>**

      Each variable underwent hypothesis testing to deem statistical significance to the model. 
      ISO was the only variable to be rejected and was replaced with HR, another power metric.  
      The linear model had a R squared value of .944, meaning 94.4% of the variability in the response variable 
      can be explained by the predictors. The model is highly accurate in capturing performance trends and 
      creating a player Impact Score.
  
## **Attachments and Contact <a id="attachments"></a>**
      


  I have attached a full report of this study as well as the data that was used. 

    Please feel free to reach me at gwentzel@binghamton.edu or on 
    linked in at "https://www.linkedin.com/in/gavinwentzel/"
