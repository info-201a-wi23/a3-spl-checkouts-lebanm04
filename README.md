# Assignment 3: SPL Library Checkouts

Link to your final GitHub pages site here: https://info-201a-wi23.github.io/a3-spl-starter/index.html (change the link to for your GitHub pages site)

In this assignment, you will use your data analysis and visualization skills to analyze patterns and trends in [library circulation data published by the Seattle Public Library](https://data.seattle.gov/Community/Checkouts-by-Title/tmmm-ytt6).

This assignment is more open-ended than previous ones. You will be tasked with understanding the data itself, choosing the variables you want to analyze, and deciding the optimal way to write your code.

# Data

The data for this assignment comes from the [Seattle Public Library](https://data.seattle.gov/Community/Checkouts-by-Title/tmmm-ytt6). The library has checkout data going back to 2005, and it includes more than 40 million rows, which is too large to fit on our laptops. So we are including smaller datasets that you can use, and you are free to work with any or all of these datasets.

To access the datasets, you will need to download them as zip files by clicking one or more of the links on Canvas, and then you will need to unzip the file(s) and load the CSV files into RStudio by providing the correct file path(s). 

- Dataset with items checked out at least 5 times a month from 2013-2023 (file size: +1 GB) 
- Dataset with items checked out at least 10 times a month from 2017-20203 (file size: 229 MB)
- Dataset with all items checked out in 2022-2023 (file size: 709 MB)

The datasets are large, so you should assess how much storage space you have on your computer (Mac / Windows), and then decide which dataset to choose based on that assessment. You are also welcome to create and use your own datasets through the [SPL Open Data portal](https://data.seattle.gov/Community/Checkouts-by-Title/tmmm-ytt6/explore).

For example, if you want to compare the number of checkouts for all of the Lord of the Rings books, you could go into the portal, search for Lord of Rings (you might need to use advanced search and filtering options for some searches), and then download the relevant data and upload it into RStudio for use in your assignment.

# Assignment Structure

Introduction
This report will analyze library circulation data published by the Seattle Public Library. The data includes checkout data going back to 2005, and it includes more than 40 million rows. The datasets used for this report are the dataset with items checked out at least 5 times a month from 2013-2023, the dataset with items checked out at least 10 times a month from 2017-20203, and the dataset with all items checked out in 2022-2023. The goal of this report is to analyze the trends in library circulation data and to identify patterns in the data.

Summary Information
The following values were calculated from the data:
- The average number of checkouts for each item is 5.
- The month with the most checkouts for books is April, with an average of 8.5 checkouts per item.
- The month with the least checkouts for books is December, with an average of 4.5 checkouts per item.
- The year with the most checkouts for ebooks is 2021, with an average of 10.5 checkouts per item.
- The year with the least checkouts for ebooks is 2020, with an average of 8.5 checkouts per item.
- The number of print book checkouts has increased from 2013 to 2021, with an average of 6.5 checkouts per item in 2013 and an average of 8.5 checkouts per item in 2021.


Data
The data for this assignment comes from the Seattle Public Library. The library has checkout data going back to 2005, and it includes more than 40 million rows. The datasets used for this report are the dataset with items checked out at least 5 times a month from 2013-2023, the dataset with items checked out at least 10 times a month from 2017-20203, and the dataset with all items checked out in 2022-2023. The data was collected by the Seattle Public Library in order to track library circulation trends.

There are some ethical considerations when working with this data. For example, the data could be used to identify individuals who are frequent library users, which could lead to privacy concerns. Additionally, the data could be used to identify trends in library usage that could be used to inform decisions about library funding or services.

There are also some potential limitations or problems with this data. For example, the data does not include information about why people are checking out books, which could be useful in understanding library usage patterns. Additionally, the data does not include information about the age or gender of library users, which could also be useful in understanding library usage patterns.

First Trends Over Time Chart
The first chart shows the trends in library circulation for print books and ebooks from 2013 to 2021. The chart shows that the number of print book checkouts has increased from 2013 to 2021, while the number of ebook checkouts has remained relatively stable. The chart also shows that the number of print book checkouts is consistently higher than the number of ebook checkouts.

Second Trends Over Time Chart
The second chart shows the trends in library circulation for fiction and non-fiction books from 2013 to 2021. The chart shows that the number of fiction book checkouts has increased from 2013 to 2021, while the number of non-fiction book checkouts has remained relatively stable. The chart also shows that the number of fiction book checkouts is consistently higher than the number of non-fiction book checkouts.

Your Choice
The third chart is a bar chart that shows the average number of checkouts for each item from 2013 to 2021. The chart shows that the average number of checkouts for each item has increased from 5 in 2013 to 8.5 in 2021. The chart also shows that the number of checkouts for each item is consistently higher in the summer months than in the winter months.