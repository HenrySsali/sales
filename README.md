## PRODUCT SALES ANALYSIS 

## 🙋‍♂️IMPRESSION.

__.Every modern company all over the world that operates e-commerce website/apps now aims to maximise sales through getting data from the customer user experience on their platforms.The immense data handed to us is to determine what time of day has the highest user activity in terms of the transcations the customers have made in purchsing the products.__

## Prerequisities.
|Pandas           |Matplotlib   |
|:----------------|:------------|
|Data Manipulation|Visualisation|

__❓Before we deive into the project ,the data that we have looks to be limited to us and not straight forward to get the solutions for the our question.__

__❓Our focal point is to find the time of the day that has an immense  trascations that have happened.And from there we can get the answers and make decisions.__

__👇 Are steps and their explanations on the way how i managed to achieve the answers to the questions.The steps are from 1-6.__

## STEPS AS INDICATED 

__🪜1__
__We started by importing all the neccessary libraries required ie pandas and matplotlib and the data was imported and printed out.__

__🪜2__
__After investigating the data ,no value was missing and we have 4 columns and 581 rows.The columns are Name,Email,Product and Transaction Date.__

__🪜3__
__Anew column called Time with DateTime formate is extracted from  Transcation Date column.__

__🪜4__
__From the Time column we need to extract hours from it to create a seperate HOUR column so that we can identify the busiest hours.__

__🪜5__
__We then require the “n” busiest hours. For that, we get the first “n” entries in a list containing the occurrence rates of the hours when the transaction took place. To further simplify the manipulation of the provided data in Python, we may utilize value counts for frequencies and tolist() to convert to list format.We stack the hour and frequencies together to cummulate the results.__

__🪜6__
__For data visualization, we will proceed with Matplotlib for better comprehensibility, as it is one of the most convenient and commonly used libraries to plot the data graphically.__

__The X-axis takes up the values of hours and Y-axis takes up the importance of the number of transactions that occured.__

__All the above steps are demostrated here https://github.com/HenrySsali/sales/blob/main/ACTIVE_SALES.pdf__

## INFERENCE
__The results are indicative of how sales typically peak in late evening hours prominently, and this data can be incorporated into business decisions to promote a product during that time specifically as shown here https://github.com/HenrySsali/sales/blob/main/image.png.__







