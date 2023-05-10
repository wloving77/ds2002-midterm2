# ds2002-midterm2

## This is the midterm for the second capstone project of ds2002 at UVA


# The entire project is split between two notebooks and some included SQL scripts and images as proof. 

1. The first notebook run is the data_initializer which loads all of the data into an Azure MySQL database and a MongoDB NoSQL database
2. The second notebook demonstrates the structured streaming capabilites of Azure Databricks and Spark by creating a fact_cannabis table and loading it into both MySQL and MongoDB. 


## Notes that are also included at the bottom of data_initializer.ipynb: 
1. There are four images in the images directory that show the state of the database's after the structured streaming in Azure Databricks and before
2. The Cannabis Data I sourced from Kaggle did not have any date style column so my date dimension is largely unused unfortunately, I still included it regardless. 
3. I hope using Mongo here in the jupyter notebook is enough to get credit for using it as I stuck mostly to loading from SQL after it was initialized here.
