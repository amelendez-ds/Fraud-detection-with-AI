# Fraud Transaction Detection with Artificial Intelligence
AI Banking - Detecting fraud transactions with different Machine Learning Algorithms

## Description
This is an independent project on *Binary Classification* with **Machine Learning** and **Deep Learning** Using the [Credit Card Fraud Detection](https://www.kaggle.com/mlg-ulb/creditcardfraud) dataset, from Kaggle I studied three different ways of implementing an automatised detection of illegal transactions. This was a very good practice of **data preprocessing** of **highly unbalanced** datasets, **Exploratory Data Analysis**, **visualizations**, **Machine Learning algorithm tuning** and compared **performance evaluation**. 

## Data
As stated above, the data can be downloaded from [Kaggle](https://www.kaggle.com/mlg-ulb/creditcardfraud). It contains transactions made by credit cards in September 2013, during two days, by european cardholders.

- 284,807 transactions, 492 frauds (0.172%)

"It contains only numerical input variables which are the result of a PCA transformation due to confidentiality issue. The only features which have not been transformed with PCA are 'Time' and 'Amount'. Feature 'Time' contains the seconds elapsed between each transaction and the first transaction in the dataset. The feature 'Amount' is the transaction Amount, this feature can be used for example-dependant cost-senstive learning. Feature 'Class' is the response variable and it takes value 1 in case of fraud and 0 otherwise."


## Models
The first two models are Machine Learning are classical **Random Forest** and **Linear Regression** for classification. Both of them have their hyperparameters tuned via Grid Search Cross-Validation. 

The more advance algorithm is an **Auto-Encoder**, a type of Neural Network that uses reconstructed representations of the data after compressing them (encoding-decoding process). The idea behind this approach was that we would train the architecture on Non-Fraud entries, and once the encoder-decoder was trained, try to classify it with its error testing it with the complete dataset. It delivers best results of all algorithms. 

## Project Structure
1. Fetching and Cleaning Transactions Dataset
2. Exploratory Data Analysis
3. Data Preprocessing
4. Building the Models
5. Performance Reports and Conclusions

## Notes
This project is succeptible of several changes and algorithm improvement. Its purpose was self challenge with very specific data that had to do with **Finance Technology**, hence getting some hands-on real world **banking problems**. The more I improve in my skills, the more I will be updating the projects.  
