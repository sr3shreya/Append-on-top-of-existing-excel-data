# Append-on-top-of-existing-excel-data
My initial usecase was to append data from a newly created dataframe onto top of already existing data in an excel sheet of a workbook.
Append function waas rewriting the same dataframe again and again.
Here is a workaround.
The code inserts blank rows on the top of already existing data.
No. of rows is calculated as per the size of Panda's Dataframe.
And append the DF into the blank rows created.
