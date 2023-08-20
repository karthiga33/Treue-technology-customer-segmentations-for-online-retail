# Treue-technology-customer-segmentations-for-online-retail

IMPORTING THE LIBRARIES:

     Importing the libraries are numpy, pandas, marplotlib, Standard Scalar, Kmeans
     
UPLOADING THE CSV FILE:

      Uploading the CSV file using pandas library and read the csv file
      
      To check the Shape, info, and describe of that datasets

PERFORMIN EXPLORATORY DATA ANALYSIS:

       To check the null values present in the data sets using isnull().sum()

       Drop the all null values using dropna 

       Chek the unique values of given datasets

Analysing the Customers based on 3 factors:

        Recency : Number of days since last purchase
        
        Frequency: Number of transactions
        
        Monetary: Total Number of transactions

        Plot the Amount, Frequency, Recency using boxplot

REMOVING OUTLIERS:

         Removing the Outliers for Amount, Frequency, Recency  using Quantile mathods

MODEL CREATING:

          Import the k means cluster classifier , 
          because this is unscaled data so we use k means clusters

          Using the elbow method choosing the k values 

          plot the k values

CONCLUSION:

           1. Customers with Cluster Id 2 are the customers with
           high amount of transactions as compared to other customers.
           
           2. Customers with Cluster Id 2 are frequent buyers.
           
           3. Customers with Cluster Id 0 are not recent buyers and hence 
           least of importance from business point of view.

       

       
