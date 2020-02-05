# Survey-Data-Analysis
How to open stat file in R
How to open a dhs stata format file in R 
In order to open your stata file in R We must first install the haven package using the following code
install.packages("haven") 
Once installed here is how we can import the survey data in R using the following code 
library(haven) 
Exercise <- read_dta("E:/R tutorial/Exercise.dta") 
*Exercise is the name assigning the data set <- is assighnment operator read_dta is the code for reading stata data #We can just change these codes depending on the type of format of data we have ("E:/R tutorial/Exercise.dta") is the path that which provides the location of the data. Here we can see that E is the E(Computer Disk), tutorial(Folder name) Exercise.dta(Stata data format name) 
Finally we can View data using the below code. 
View(Exercise)
