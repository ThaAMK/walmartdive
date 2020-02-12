# walmartdive
this is to have a general look for walmart weekly sales and the factors that affect this data
communicates

    the libraries used (optional -- how to install)
    in this project we used the following libraries:
      numby # linear algebra
      pandas # data processing
      matplotlib.pyplot for drawing graphs
      google.colab to use google drive
      sklearn.impute to deal with nulls
      
 this project was choosen beacause of my intrest on understanding human behaviour and motives
 
 the files used in the project as below:
 stores.csv

This file contains anonymized information about the 45 stores, indicating the type and size of store.

train.csv

This is the historical training data, which covers to 2010-02-05 to 2012-11-01. Within this file you will find the following fields:

    Store - the store number
    Dept - the department number
    Date - the week
    Weekly_Sales -  sales for the given department in the given store
    IsHoliday - whether the week is a special holiday week

test.csv

This file is identical to train.csv, except we have withheld the weekly sales. You must predict the sales for each triplet of store, department, and date in this file.

features.csv

This file contains additional data related to the store, department, and regional activity for the given dates. It contains the following fields:

    Store - the store number
    Date - the week
    Temperature - average temperature in the region
    Fuel_Price - cost of fuel in the region
    MarkDown1-5 - anonymized data related to promotional markdowns that Walmart is running. MarkDown data is only available after Nov 2011, and is not available for all stores all the time. Any missing value is marked with an NA.
    CPI - the consumer price index
    Unemployment - the unemployment rate
    IsHoliday - whether the week is a special holiday week

to summriez the analysis, we can say that sales if walmart is affected by very different factors, some of them are contreducting each other, for example ( sales increase during holidays and modirate tempretures, but majority of the holidays are during winter).
