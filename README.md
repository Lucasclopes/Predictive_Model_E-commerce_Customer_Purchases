# E-commerce Predictive Model
 
**Summary:** Build a predictive model that answers the question “Which customers are more likely to buy our products?” using data from the existing customer database

**Keywords**: Python, Predictive Model, Machine Learning, Neural Networks, Decision Trees, Random Forest, Gradient Boost

## Important libraries and packages 
- pandas, numpy
- seaborn, matplotlib
- sklearn(ensemble, model_selection, feature selection)

## Steps
- ### Import the data
- ### Data Exploration (missing values, coherence checking)
- ### Feature Enginnering and Selection (metric and non-metric features)
- ### Model Training (several models were tested: KNN, NN, Naive Bayes, Decision Trees, SVM, Random Forest, ADA Boost, Gradient Boosting, ect)
- ### Grids, Tuning, Test Performance
- ### Deployment

## Data
- Data fields
- Access_ID - Unique identification of the user access to the website
- Date - Website visit date
- AccountMng_Pages - Number of pages visited by the user about account management
- AccountMng_Duration - Total amount of time (seconds) spent by the user on account management related pages
- FAQ_Pages - Number of pages visited by the user about frequently asked questions, shipping information and company related pages
- FAQ_Duration - Total amount of time (seconds) spent by the user on FAQ pages
- Product_Pages - Number of pages visited by the user about products and services offered by the company
- Product_Duration - Total amount in time (seconds) spent by the user on products and services related pages
- GoogleAnalytics_BounceRate - Average bounce rate value of the pages visited by the user, provided by google analytics
- GoogleAnalytics_ExitRate - Average exit rate value of the pages visited by the user, provided by google analytics
- GoogleAnalytics_PageValue - Average page value of the pages visited by the user, provided by google analytics
- OS - Operating System of the user
- Browser - Browser used to access the webpage
- Country - The country of the user
- Type_of_Traffic - Traffic Source by which the user has accessed the website (e.g., email, banner, direct)
- Type_of_Visitor - User type as "New access", "Returner" or "Other"
- Buy - Class label indicating if the user finalized their actions in the website with a transaction
