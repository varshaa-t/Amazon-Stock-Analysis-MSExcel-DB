# Amazon-Stock-Analysis-MSExcel-DB

## About Amazon

Amazon.com, Inc. is an American multinational technology company that focuses on e-commerce, cloud computing, digital streaming, and artificial intelligence. It is one of the Big Five companies in the U.S. information technology industry, along with Google, Apple, Microsoft, and Facebook. The company has been referred to as "one of the most influential economic and cultural forces in the world," as well as the world's most valuable brand. 

## About the Dataset

The dataset provides historical data at the daily level from December 2020 to November 2021. Their columns include the following:

- Date : Date the data was recorded
- Open : Price from the first transaction of a trading day
- High : Maximum price in a trading day
- Low : Minimum price in a trading day
- Close : Price from the last transaction of a trading day
- Volume : Number of units traded in a day

All displayed currencies are in USD.

## Analysis Derived from the Dataset

- On any given day, the company's value is just as likely to increase as it is to decrease.

<img src="https://user-images.githubusercontent.com/60147227/220074019-3ebaf137-9e0a-4262-8866-8341c36f2ea7.png" width="300">

- July 2021 had the highest Average Closing Value

<img src="https://user-images.githubusercontent.com/60147227/220075456-e98064a9-d9a2-4410-8d52-fd40c6caf79e.png" width="450">

- There is a very strong linear relationship between the daily High and Low values. As one variable increases/decreases, so does the other. With an R-squared value very close to 1, almost all the variability in one variable can be explained by the variability in the other.  

<img src="https://user-images.githubusercontent.com/60147227/220076451-d72b17c3-25f5-4b48-9e48-8d7acac130c3.png" width="650">

- Half of the time, the number of units traded in a day was roughly between 1.5 and 3.0 million and the other half of the time, roughly between 3.0 and 10.0 million units were traded. Usually, 5.7 milllion or fewer units were traded in a day but one day in the year saw as many as 10 million units traded.

<img src="https://user-images.githubusercontent.com/60147227/220077393-fa00fc3a-8a30-436d-b8f3-9d9fd8fff6a9.png" width="550">

- Maximum trading occurred on 30th July 2021 with approximately 9.96 million units traded that day. Minimum trading occurred on 24th December 2020 with approximately 1.45 million units traded that day. There does not seem to be any particular pattern with respect to the number of units being traded throughout the year. Most days see the trading of between 2 and 6 million units. The number of Amazon units traded dropped from 9.96 million to 2.18 million from 30th July 2021 to 4th August 2021.

<img src="https://user-images.githubusercontent.com/60147227/220078065-7739327d-d003-4c98-bd11-16cd833142ab.png" width="600">

- Although it's not always perfect, there does appear to be a relationship between the daily High-Low difference and the number of units traded. Loosely speaking, when the High-Low difference is larger, more units are traded. Conversely, when the High-Low difference is smaller, fewer units are traded.

<img src="https://user-images.githubusercontent.com/60147227/220078553-bcc805c7-b60c-4bdd-93e8-2484380d15b8.png" width="1500">

