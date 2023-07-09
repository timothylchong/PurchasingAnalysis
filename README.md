# PurchasingAnalysis

## Original Dataset: https://www.kaggle.com/datasets/raosuny/e-commerce-purchase-dataset?resource=download

## For this project, we are trying to find the customers who spent the most money and the biggest sales day of the week; this was to optimize sales. We are also trying to be aware of the space/time complexity of our program.

## To do this, utilize these libraries:
- Pandas (ETL process)
- Calendar (to convert dates into days of the week
- Collections (to see how many unique days were in the data set)
- Matplotlib (for visualizations)

### First, import the dataset into a pandas dataframe and drop any redundant columns (I removed the column 'Unnamed: 7')
### Second, we find the customer who spent the most money by utilizing groupby(); I created another dataframe to seperate these findings
### Third, utilize the calender's Timestamp function to get all of the days of the week associated with the dates in the dataset; afterward, use groupby() to get all of the sales for each week
### Fourth, I used collections' Counter() to get the frequency of purchases on all of the dates
### Fifth, I graphed the amount of purchases per day with the frequency being on the y-axis and thedate being on the x-axis

## The data was unbalanced, therefore there is one day that has about 3 times more purchases than any other day. To possibly counteract that, I should have found the day of the week that appeared the most rather than the amount of purchases in a single day. 


