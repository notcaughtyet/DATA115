# DATA115
DATA115 Personal Data Set

The purpose of this project is to explore and analyze data sets that may contain information regarding how to ensure security and efficiency in communications systems. This is accomplished by analyzing the CSRIC's Best Practices Suggestions dataset in order to extract the most important and frequently-appearing keywords in order to know which areas need to be focused on. I checked the data for any required cleaning, and deconcatenated keywords into separate columns

Let's make a barplot to display the most frequently mentioned keywords. I converted the Keywords file to a pivot table in Excel to count the number of keywords.

![Keywords Pivot Table Count of Occurrences](https://github.com/notcaughtyet/DATA115/blob/main/Keywords%20Count.png)

I plotted this data in RStudio using ggplot:

![Keywords Barchart count of occurences](https://github.com/notcaughtyet/DATA115/blob/main/Keyword%20Barchart.png)

Then I repeated the process, but this time calculated an average of their priority instead.

![Pivot table of keyword priority](https://github.com/notcaughtyet/DATA115/blob/main/Average%20of%20Priority.png)

![Keyword barchart by priority](https://github.com/notcaughtyet/DATA115/blob/main/Keyword%20Priority.png)

Some keywords don't have enough occurences to accurately calculate their average priority, so then I redrew the plots while omitting any keywords with less than 10 occurences.

![Keyword barchart by priority -- top occurrences only](https://github.com/notcaughtyet/DATA115/blob/main/Keyword%20Priority.png)
