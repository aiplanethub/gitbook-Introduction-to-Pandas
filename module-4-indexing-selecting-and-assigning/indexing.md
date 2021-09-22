# Indexing

### What is Indexing in Pandas?

* Indexing in Pandas means selecting particular rows and columns from a DataFrame 
* Indexing in Pandas is same is same as we did for a Python List and a NumPy array 
* Pandas has two known operators used for indexing. 
* There are two different methods of indexing in Pandas:
  * **loc - label based selection iloc - index based selection**

### Index Based Selection

* Index - based selection is to select data based on its numerical position in dataframe.  
* **iloc** is used for selecting data based on numerical position 
* The syntax for using **iloc** operator is `df.iloc[ ]`, where df is a dataframe name. You can pass the numerical positions of rows and columns to select in the square bracket. 
* Do you remember the indexing in a NumPy array? If not, don’t worry, you will soon see its implementation on a dataset. 
* Import Pandas Library and load ‘exam\_scores.csv’ file

![](https://lh5.googleusercontent.com/4dCqek__DOPxROW7RZwChJvhiR0DvbMU6gxWZG7ZCavlIwWA8frOXPLcIDFY_FPEQ_B3YPctn_v_-kDVGHm_B4IpJDpwLFiF5Irqzo2WEI8yFedZFZtS1PwWIAQsCHL_qFGTYw0kfw8=s0)

* **Selecting data based on its numerical position. Used operator - iloc**

![](../.gitbook/assets/image%20%281%29.png)

* **Selecting data based on its numerical position. Used operator - iloc**

![](https://lh5.googleusercontent.com/nLa56yAfpy7qYDyqiqKxeIa3r0hFvOHr-2ZShpPG2qeVWjiBu2WH-2lG7rkKeEhE7zAQS7RJAjY-5nKXm9YAbBuUcDUpksZr3qtMMRV1C6ykhP_LARkhz6wBP463lzfQV5rm-r3mTkA=s0)



* **Selecting data based on its numerical position. Used operator - iloc** 
* You can also pass **list of indexes**

![](../.gitbook/assets/image%20%283%29.png)

* Selecting data based on its numerical position. Used operator - **iloc** 
* You can also pass **negative indexes**

![](../.gitbook/assets/image%20%289%29.png)

### Label Based Selection


* Label based selection selects data based on the column or row names/index. This becomes important while selecting data from a dataframe 
* Label based selection is done with loc 
* Do you remember the python default indexing of the dataframe and the indexes/names that you changed in the previous topics? 
* loc and iloc are conceptually similar. The difference is that iloc considers the default indexing while loc ignores the default indexing 
* **loc** is used for selecting data based on the data index value/name, not the numerical positions.  
* The syntax for loc is similar to iloc: `df.loc[ ]`, df is a dataframe. 
* We will learn about its implementation on a dataset soon. 
* Selecting data from a dataframe using column and row names/index. Used operator - loc

![](../.gitbook/assets/image%20%282%29.png)

