# investment-case-study
To identify the best countries and a suitable investment type for making the investment. The overall strategy is to invest where others are investing, implying that the best countries are the ones ‘where most investors are investing’

language used -python

library used:
-pandas,numpy



![image](https://github.com/Ashuk2810/investment-case-study/assets/97400304/23b044ed-71f6-43a0-9509-e8cdf2281761)

Introduction to the Problem Statement.

     ● The Objective is to identify the best countries and a suitable investment
       type for making the investment.

     ● The overall strategy is to invest where others are investing, implying that the
       best countries are the ones ‘where most investors are investing’


Data Description

     ● The data  is a real investment data taken from crunchbase.com

     ● The First part is the details of the companies given in the Companies.txt file and
       the second part is the rounds2 file which contains the details of the investments
       made.

Data Cleaning Steps

    ● In the rounds2 (1).csv file converted it into a Excel file for easy reading
      of the data.

    ● Since Python is case sensitive,changed the fonts of
      ‘Company_permalink’(Unique ID) and ‘Permalink’ columns(Unique ID) to
      UPPER.

    ● removed the duplicate observations from the data.

    ● calculated the percent of Null values in each columns and identified
      redundant columns and dropped them.

    ● then merged the two given data frames into one for this analysis

Problem Solving Steps

    ● The problem has been solved as per the following steps:

        ○ 1. Reading the data from the text and csv files.

        ○ 2. Cleaned the data (UPPER case for Unique ID, removed duplicates, dropped redundant
             columns and merged the data frames)

        ○ 3. Next performed some basic analysis of the given data such as by identifying the percent
             missing values, creating a PIVOT table, and filtering the data.

        ○ 4. then went on to find the top 9 countries i.e., the countries with highest investment for the
             Venture type of investment.

        ○ 5. then extracted the main category from the category list using the string function

        ○ 6. next categorised the Investments made as Type A, Type B and Type C with respect to the
            amount raised.

Takeaways & conclusions

       ● Through the analysis we have identified the top 10 investment types and the top
         10 countries based on where most investors are investing.

       ● Since ‘venture type’ is having the most investment and, ‘USA’ is having the
         highest investment.

       ● It will be best to invest in ‘Venture types funding in USA’ as it is the best
         country and most suitable investment type

