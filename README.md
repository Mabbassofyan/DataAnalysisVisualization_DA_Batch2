**DataAnalysisVisualization_DA_Batch2**
---  ------         --------------  -----      
**Intro:**

Our project aims to analyse the rating of the best 1000 film on IMDB website using numpy, pandas, matplotlib.pyplot, and seaborn libraries. In addition, predicting IMDB rating based on gross and runtime along with classifying IMDB rating as "High" or "Low" based on gross and runtime.  

**Objective:**

To help identify audience preferences, which can make us focus more on specific genres prioritizing the acquisation or production of more content in popular genres like Drama, Action, and Crime. Also helping production companies make the best decision in terms of film production.

**About Dataset:**

Our dataset has different information regarding films contained in a total of 16 columns.

**Data columns:**

          
 No   Column         Non-Null Count  Dtype         
---  ------         --------------  -----      

 0   Poster_Link    1000 non-null   object        
 
 1   Series_Title   1000 non-null   object        
 
 2   Released_Year  999 non-null    datetime
 
 3   Certificate    899 non-null    object        
 
 4   Runtime        1000 non-null   object        
 
 5   Genre          1000 non-null   object        
 
 6   IMDB_Rating    1000 non-null   float64       
 
 7   Overview       1000 non-null   object        
 
 8   Meta_score     1000 non-null   float64       
 
 9   Director       1000 non-null   object        

 10  Star1          1000 non-null   object        
 
 11  Star2          1000 non-null   object        
 
 12  Star3          1000 non-null   object        
 
 13  Star4          1000 non-null   object        
 
 14  No_of_Votes    1000 non-null   int64         
 
 15  Gross          1000 non-null   float64       

 ---  ------         --------------  -----  


## Project Workflow

The project is structured around the following key phases:

1. **Data Acquisition and Preprocessing:**
    * Obtaining the IMDB top 1000 films dataset.
    * Cleaning the data by handling missing values, removing outliers, and ensuring data consistency.
    * Transforming data into a suitable format for analysis.

2. **Exploratory Data Analysis (EDA):**
    * Investigating the distributions of key variables (e.g., IMDB rating, runtime, gross).
    * Identifying relationships between variables using correlation analysis and visualization techniques.
    * Exploring patterns and trends within different movie genres and release years.

3. **Statistical Modeling:**
    * Building predictive models to understand the factors influencing IMDB ratings.
    * Utilizing regression models to estimate the relationship between features and ratings.
    * Evaluating model performance using metrics like Mean Squared Error (MSE) and R-squared.

4. **Data Visualization and Reporting:**
    * Creating insightful visualizations (histograms, scatter plots, box plots, etc.) to communicate findings effectively.
    * Generating comprehensive reports summarizing the key insights and recommendations derived from the analysis.

5. **Regression and Classification:**
    * Creating insightful predections.
    * Generating comprehensive predections and recommendations.
      

## Technologies Used

* Python
* NumPy
* Pandas
* Matplotlib
* Seaborn
* Regression Model
* Classification Model

  
## Steps:

•	Importing the libraries

•	Choosing the data

•	Cleaning the data and removing outliers along with null values

•	Organizing the data

•	Analyzing the data

•         Representing the data using various visualization means

•	Predicting IMDB rating based on gross and runtime.

•	Classifying IMDB rating as "High" or "Low" based on gross and runtime.

