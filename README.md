# Exploratory Data Analysis (EDA) of the Titanic Dataset
Table of contents
  - Overview
  - Features
  - Requirements
  - Usage
  - Dataset
  - Results
  - Conclusion
  - Acknowledgements
## Overview
This project looks into the Titanic dataset from Kaggle, focusing on:
- Survival rate analysis by passenger class, gender, and age
- Data cleaning and missing value handling
- Visualization of key patterns and relationships
- Statistical insights into survival factors

Developed with python's data science tools
- Pandas for data manipulation
- Matplotlib/Seaborn for visualization
- Jupyter Notebook for interactive analysis

  ## Features
  - Analysis of survival rates by:
     - Passenger Class(Pclass)
     - Gender
     - Age groups
  - Missing data handling for Age and Cabin features
  - Correlation between variables
 
  ## Requirements
    - Python 3
    - Jupyter Notebook
    - Libraries:
       - pandas
       - numpy
       - matplotlib
       - seaborn
  ## Usage
  - Launch Jupyter Notebook:
  - Open titanic_eda.ipynb
  - Run cells sequentially to reproduce analysis
  ## Dataset
   The dataset contains 891 passenger records with 12 fearures:
       - Survival srarus (Survived)
       - Passenger class (Pclass)
       - Name, Sex, Age
       - SibSp (Siblings/spouse)
       - Parch (parents/children)
       - Tickit number, Fare, Cabin
       - Embarked (port)
       - PassengerId
           Source: Kaggle Titanic Machine Learning From Disaster
  ## Results
   Key findings:
      - Overall survival rate:38.4
      - Female survival rate: 74.4% vs male survival rate: 18.9%
      - 1st class passengers had 62.9% relative to 3rd class: 24.2%
      - Children under 12 had highest survival rate(59.0%)
   Visualization included:
   - Survival by class and gender
   - Age distribution histograms
   ## Conclusions
  Main takeaways
   - The survival data clearly  shows that women and children were given priority.
   - Survival rates were higher among those of higher socio-economic rank (Pclass 1).
     Future work directions
       * Feature engineering for cabin data
       * Machine learning modeling
       * Advanced visualization techniques
    ## Acknowledgements
     * Dataset source: Kaggle
  
  
      
  
  
