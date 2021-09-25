# Renaming



* Renaming means changing the name. 
* Most of the time we get dataset where column names are not satisfactory.  
* For example in this dataset the 'math score', 'reading score' and 'writing score' contains spaces in it due to which we are not able to use attribute\(dot\) selection style method to select a particular column.  
* And not only this if the column names were 'ms' for math score, 'rs' for reading score and 'ws' for writing score, these are not satisfactory column names. The need of renaming a column or index comes here. 
* Pandas provides a function ‘rename\(\)’ to rename column/indexes in a dataframe. 
* Let's rename all the column names in our dataframe which contains spaces in it. Also we will rename the column 'race/ethnicity' to 'race'.

![](../.gitbook/assets/screen-shot-2021-09-25-at-3.48.22-pm.png)

* We can get the list of all the columns using an attribute columns.

![](https://lh6.googleusercontent.com/NusuwzNCgDdQ53GQDUA5O_7caeS2uwbxLKFzdvq5JembIsTBFr7QROlmvMChihWsbuMJUKi0sMAu0z_n65HsZkW7KpO-RfCBN_rm3YjJrkScPuHyA5OUELN3n5a5OWjYOWskW45tN4Y=s0)

![](https://lh4.googleusercontent.com/bO-d-nzNgeJ0cLUApgoffNli6VFVV4ut9uQnWJK9Z-ij6o-sizyjGT8kwa7OP7Ts80uTLPXkS0RZafkcWUM6aWe5KjEwmNZTXRU4RfHkPJ4PtTEEJ04EEsLTyT8PGrJ8b7b2wxh4a3o=s0)

* We can also rename the indexes of the dataframe using the rename\(\) function as shown in the image below.

![](../.gitbook/assets/screen-shot-2021-09-25-at-5.38.50-pm.png)

![](../.gitbook/assets/screen-shot-2021-09-25-at-5.39.30-pm.png)

