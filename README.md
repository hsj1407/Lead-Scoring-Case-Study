# Lead-Scoring-Case-Study
 <h1>Busines Problem: </h1><br>
        
      
<h3>About Company and its sales Process:</h3>

- An education company named X Education sells online courses to industry professionals.
- The company markets its courses on several websites and search engines like Google. 
- Once these people land on the website, they might browse the courses or fill up a form for the course or watch some videos.
- When these people fill up a form providing their email address or phone number, they are classified to be a lead. 
- Moreover, the company also gets leads through past referrals. 
- Once these leads are acquired, employees from the sales team start making calls, writing emails, etc. 
- Through this process, some of the leads get converted while most do not. The typical lead conversion rate at X education is around 30%. 

<h3>Challenges for a company:</h3>

- Now, although X Education gets a lot of leads, its lead conversion rate is very poor beacuse with limited time, they are not able to focus more on the potential customers.
- The company wishes to identify the most potential leads, also known as ‘Hot Leads’. 
- If they successfully identify this set of leads, the lead conversion rate should go up. 
- As the sales team will now be focusing more on communicating with the potential leads rather than making calls to everyone. 
- X Education wants to select the most promising leads, i.e. the leads that are most likely to convert into paying customers.
        
<h3>Company's Requirement:</h3>

The company requires a prediction model wherein a value to be assigned to each of the leads, called lead scores, such that the customers with a higher lead score have a higher conversion chance and the customers with a lower lead score have a lower conversion chance. The CEO, in particular, has given a ballpark of the target lead conversion rate to be around 80%.

<h3>Goals of the Case Study:</h3>

There are quite a few goals for this case study:

1. Needs to build a logistic regression model to assign a lead score between 0 and 100 to each of the leads which can be used by the company to target potential leads. A higher score would mean that the lead is hot, i.e. is most likely to convert whereas a lower score would mean that the lead is cold and will mostly not get converted.

2. There are some more problems presented by the company which this model should be able to adjust to if the company's requirement changes in the future so the predictive model should also able to handle those problems as well. 


## Steps Involved

1. Loading Required Liabraries
2. Setting View Options
3. Read Data Dictionary
4. Read and Understand the Data
5. Exploratory Data Analysis
    1) Univariate Analysis
        1) Data Cleaning and Sanity Checks
            1) Dropped columns based on number of unique values
            2) Dropped Columns unrelated to studies.
        2) Understand Target Varaible
        3) Missing value Treatment
        4) Count plot and Coversion rate plot
        5) Countplot for each Categorical Feature
            1) Outliers Treatment
                1) Distribution PLot: Contnious plot
            2) Capping and Trimming
                2) Boxen PLot
            3) Capping and Trimming
    2) Bivariate Analysis
        1) Stacked Bar chart: Conversion Rate
        2) Correlation using chi-square between categorical Variable.
        3) Heatmap CramersV: Correlation within Nominal Varaible
    3) Multivariate Analysis
        1) Heat Map Correlation Chart
        2) Pair Plot
  
6. Modeling
    1) Data Preparation for modeling
        1) Create Dummy Varaibles
        2) Train Test Split
        3) Stndard Scaling 
    2) Feature Elimination
        1) Check for Multicollinearity: Vif
        2) RFE
    3) Making Models
        1) statsmodels.api.GLM
        2) Logistic Regression
        3) optimal cutoff
        4) roc
        5) precision recall trade off
        6) Model Evaluation
        7) Model Scores
        8) Ks statisatics and lift plot
        9) Cross validation scores
        10) Test Predictions and Evalusation
    
    4) Compares resilts for each Model
    
    5) Relative information of final Parameters
    
    6) Lead score bw 0-100 for each lead.<br>
    
    7) Final suggestion and insights<br>

