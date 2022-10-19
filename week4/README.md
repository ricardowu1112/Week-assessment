# FTDS-week3-test

### Problem 1
 Go to this website [https://data.gov.hk/en-data/dataset/wkcda-wkcarpark-wkcarpark]\
 Read the documentation about how to make a request for the West Kowloon car park information.

 There are only two car parks in the data.

 Now, create a function ```CarParkInfo()``` such that it pulls data from the API and returns a list with four elements with the exact order as follows:\
 ```[1st element, 2nd element, 3rd element, 4th element]```

 The elements are as follows:
 - 1st element is the English name of the first carpark. 
   - i.e. ```'Xiqu Centre Car Park, West Kowloon Cultural District'```
 - 2nd element is the height limit of the first carpark. 
   - i.e ```2.45```, in which its data type is a float.
 - 3rd element is the English name of the second carpark.
 - 4th element is the height limit of the second carpark.

-------------
### Problem 2

Scrape the first 3 pages of the book catalogue available in http://books.toscrape.com/ and find the total sum of the prices of the books shown in the first 3 pages. Your function ```findTotalSum()``` should have an input parameter of *n*, indicating the first *n* pages it will scrape. The function should return the sum with type ```float```. 