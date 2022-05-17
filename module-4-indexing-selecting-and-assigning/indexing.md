# Indexing

## What is Indexing in Pandas?

* Indexing in Pandas means selecting particular rows and columns from a DataFrame&#x20;
* Indexing in Pandas is same as we did for a Python List and a NumPy array&#x20;
* Pandas has two known operators used for indexing.&#x20;
* There are two different methods of indexing in Pandas:
  * **loc - label based selection**
  * **iloc - index based selection**

## Index Based Selection

* Index - based selection is to select data based on its numerical position in dataframe. &#x20;
* **iloc** is used for selecting data based on numerical position&#x20;
* The syntax for using **iloc** operator is `df.iloc[ ]`, where df is a dataframe name. You can pass the numerical positions of rows and columns to select in the square bracket.&#x20;
* Do you remember the indexing in a NumPy array? If not, don’t worry, you will soon see its implementation on a dataset.&#x20;
* Import Pandas Library and load ‘exam\_scores.csv’ file

![](https://lh5.googleusercontent.com/4dCqek\_\_DOPxROW7RZwChJvhiR0DvbMU6gxWZG7ZCavlIwWA8frOXPLcIDFY\_FPEQ\_B3YPctn\_v\_-kDVGHm\_B4IpJDpwLFiF5Irqzo2WEI8yFedZFZtS1PwWIAQsCHL\_qFGTYw0kfw8=s0)

* **Selecting data based on its numerical position. Used operator - iloc**

![](https://github.com/dphi-official/Introduction-to-Pandas/blob/master/.gitbook/assets/image (1) (1).png)

* **Selecting data based on its numerical position. Used operator - iloc**

![](https://lh5.googleusercontent.com/nLa56yAfpy7qYDyqiqKxeIa3r0hFvOHr-2ZShpPG2qeVWjiBu2WH-2lG7rkKeEhE7zAQS7RJAjY-5nKXm9YAbBuUcDUpksZr3qtMMRV1C6ykhP\_LARkhz6wBP463lzfQV5rm-r3mTkA=s0)

* **Selecting data based on its numerical position. Used operator - iloc**&#x20;
* You can also pass **list of indexes**

![](https://github.com/dphi-official/Introduction-to-Pandas/blob/master/.gitbook/assets/image (2).png)

* Selecting data based on its numerical position. Used operator - **iloc**&#x20;
* You can also pass **negative indexes**

![](https://github.com/dphi-official/Introduction-to-Pandas/blob/master/.gitbook/assets/image (9).png)


## Label Based Selection

* Label based selection selects data based on the column or row names/index. This becomes important while selecting data from a dataframe&#x20;
* Label based selection is done with loc&#x20;
* Do you remember the python default indexing of the dataframe and the indexes/names that you changed in the previous topics?&#x20;
* loc and iloc are conceptually similar. The difference is that iloc considers the default indexing while loc ignores the default indexing&#x20;
* **loc** is used for selecting data based on the data index value/name, not the numerical positions. &#x20;
* The syntax for loc is similar to iloc: `df.loc[ ]`, df is a dataframe.&#x20;
* We will learn about its implementation on a dataset soon.&#x20;
* Selecting data from a dataframe using column and row names/index. Used operator - loc

![](https://github.com/dphi-official/Introduction-to-Pandas/blob/master/.gitbook/assets/Screen Shot 2021-11-03 at 8.22.02 PM.png)

