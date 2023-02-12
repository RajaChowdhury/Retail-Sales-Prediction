# Retail Sales Prediction
        			AlmaBetter Verified Project

![image](https://user-images.githubusercontent.com/104791753/218263746-d28795ba-9a5f-4723-a886-a1bd3cc09c96.png)

I have bulit a Retail Sales Prediction Model using Python which can be deployed to make sales forecast for retail stores and help them to manage inventories and makes strategies.



## Description

This project is about Rossmann company, which operates over 3000 drug stores in 7 European countries and Rossmann store managers are tasked with predicting their daily sales for up to six weeks in advance. So, the goal of the project is to predict the daily sales for a chain of drugstores (Rossmann stores) based on various factors such as promotions, competition, school and state holidays, seasonality, etc.

The data provided for this problem includes a history of daily sales for each store, along with additional information such as store location, type of store, and relevant promotions and events. The challenge is to use this data to build a model that can accurately forecast sales for each store. This can help Rossmann retail stores to optimize their supply chain, better manage their inventory and make informed decisions about promotions and other marketing strategies.



## Attribute Information

*  **Id** - an Id that represents a (Store, Date) duple within the test set
*  **Store** - a unique Id for each store
*  **Sales** (discrete)- the turnover for any given day (this is what you are predicting)
*  **Customers**(discrete) - the number of customers on a given day
*  **Open**(nominal) - an indicator for whether the store was open: 0 = closed, 1 = open
*  **StateHoliday**(nominal) - indicates a state holiday. Normally all stores, with few exceptions, are closed on state holidays. Note that all schools are closed on public holidays and weekends. a = Public holiday, b = Easter holiday, c = Christmas, 0 = None
*  **SchoolHoliday**(nominal) - indicates if the (Store, Date) was affected by the closure of public schools
*  **StoreType**(nominal) - differentiates between 4 different store models: a, b, c, d
*  **Assortment**(nominal) - describes an assortment level: a = basic, b = extra, c = extended
*  **CompetitionDistance**(continuous) - distance in meters to the nearest competitor store
*  **CompetitionOpenSince[Month/Year]**(discrete) - gives the approximate year and month of the time the nearest competitor was opened
*  **Promo**(nominal) - indicates whether a store is running a promo on that day
*  **Promo2**(nominal) - Promo2 is a continuing and consecutive promotion for some stores: 0 = store is not participating, 1 = store is participating
*  **Promo2Since[Year/Week]**(discrete) - describes the year and calendar week when the store started participating in Promo2.
*  **PromoInterval**(discrete) - describes the consecutive intervals Promo2 is started, naming the months the promotion is started anew. E.g. "Feb,May,Aug,Nov" means each round starts in February, May, August, November of any given year for that store
*  **DayOfWeek** (ordinal) - Day of the week, using 1-7 for Monday - Sunday respectively
*  **Date** (Date) - Date of the entry



## Steps Involved

* Importing Libraries And Loading The Datasets
* Overview Of The Datasets 
    *   Reading & Inspection Of First Dataset
    *   Reading & Inspection Of Second Dataset
    *   Merging both the datasets
    *   Further analysing both the datasets
* Data Wrangling And Processing
    *   Converting Dtype Of Feature
    *   Extracting Date
    *   Combining And Creating Columns
    *   Null Value Treatment
    *   Handling Outliers
* Exploratory Data Analysis
* Key Findings From EDA
* Feature Engineering 
    *   Feature Selection
    *   Correlation
    *   Dependent Variable Transformation
    *   Scaling Numberical Features
    *   Dummification
* ML Model
    *   Train-Test Split
    *   Model Training And Prediction
  		* Linear Regression
  		* Lasso Regression
  		* Ridge Regression
  		* Decision Tree Regression
  		* Random Forest Regression
  		* Gradient Boosting Regression
  		* XGboost Regression
    *  Hyperparameter Tunning
  		* Linear Regression
 		* Lasso Regression
  		* Ridge Regression
  		* Decision Tree Regression
  		* Random Forest Regression
  		* Gradient Boosting Regression
  		* XGboost Regression
	*  Cross validation
	*  Feature Importance
*  Conclusions 



## Datasets

### Rossmann Stores Data.csv - historical data including Sales
### store.csv - supplemental information about the stores

The datasets can be be downloaded from: https://drive.google.com/drive/folders/1r6-Jp7EEik4yLHgIn7bZP3xdWQv3l8Bk?usp=share_link
