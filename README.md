# Week 2 VBA Challenge
## Overview
### In this challenge, we were asked to help Steve perform an analysis on his stocks using VBA to conclude whether the stock would be worth continuing to invest in. We have been given a range of data on the stock market extending over the last few years. In order to perform a more accurate analysis on the data, we were given the task of using the code from Module 2 and streamlining it to result in a faster acting and more efficient code. 
## Analysis
### I began the project by copying and pasting the code from Excel to VBA. For some reason the original code would not open in VBA but worked fine opening in a separate Excel document. As a result of this extra step, I noticed some errors within the given code such as peculiar arrays of symbols throughout the code and spaces in random places. Once I corrected those mistakes, I began to write the code in order to make it more efficient to run the data. The first step was to create a ticker variable and three output arrays for the starting price, ending price, and volume. Next, we create a loop that will run through all 12 of the different stocks and stores the values from the different arrays. Once we establish our loop, we create a conditional statement for the starting price and the ending price. This conditional statement will match the current row with the first row and the last row, respectively, and assign a price to each variable. To see the physical data from the output, we created another loop that will give the values of the "Total Daily Volume", "Ticker", and "Return" columns on a separate spreadsheet.
![The first error I noticed within the code](https://ibb.co/ZGgxcJq)
![How I corrected the error](https://ibb.co/55CN1jB)
## Results
### The results from this code concluded that from 2017 to 2018, the stocks RUN and ENPH were consistently performing well and therefore would be worth continuing to invest in. Throughout this challenge, there were many advantages and disadvantages to cleaning up the given code using VBA. By cleaning up the code, we were able to run our program at a faster speed than it would have taken. The code is also less complicated and easier to save on your computer or share with others.Therefore, refactoring this code gives you a more accurate, faster, and cleaner analysis than the original. Some disadvantages that I noticed while going through the errors within my code was how finicky VBA can be when it runs through code. Simple spaces would disrupt the entire code and prevent anything from running. This let me know what kind of problems may arrise while refactoring code and how tedious it can be to comb through every line in order to find a mistake. 
![Run time for 2017](https://ibb.co/JtMjN7c)
![Run time for 2018](https://ibb.co/M6NYHLZ)
