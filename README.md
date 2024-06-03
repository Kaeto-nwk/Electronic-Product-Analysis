# Electronic-Product-Analysis

## Table of Contents 
[Project Overview](#project-overview)

[Data sources](#data-sources)

[Tools](#tools)

[Data preparation](#data-preparation)

[Exploratory Data Analysis](#exploratory-data-analysis)

[Results](#results)

[Recommendations](#recommendations)

[Limitations](#limitations)



## Project Overview 
This project aims to understand customer satisfaction for both brands and their products and the potential influence of customer satisfaction on brands. What I most enjoyed about this project is that some of the insights did not always match expectations and I expected that larger brands would have higher customer satisfaction.

<img width="1000" alt="image" src="https://github.com/Kaeto-nwk/Electronic-Product-Analysis/assets/150389314/26dc15d4-df22-4b86-b134-b575033d1f2b">

## Data sources

Onyx data 


Rows: 7,299


Tables: 2 


The original dataset has been added to the repository.

## Tools

Visualisation and cleaning: Power Bi, Power Query 

## Data Preparation 

I removed Blanks and duplicate values.


I converted incorrect data types to correct data types to allow for useful and relevant analysis.

## Exploratory Data Analysis

1. Have there been any trends in the overall product rating over the years?
2. Which brand was highly recommended by customers?
3. Which brand received the highest rating on average?

## Results
1. Are there any trends in the overall average product rating over the years?

Just before 2008, there was a sharp drop from a rating of 5 to a  4-star rating and then the rating rose back to 5 just after 2012. This is mainly due to the lack of reviews between 2008 and 2012, the lack of sample size had a massive effect on the overall average rating.
After 2012 there was a steady decline in the average product rating until the third quarter of 2014, where the lowest average product rating of 3.68 occurred following an increase in customer reviews and ratings, which shows that Customers were more dissatisfied with the products received.
However, after this fall in rating  the overall product rating made a positive turn and continued to climb until reaching an average product rating of 4.67.

<p align="center" width="100%">
<img width="700" alt="image" src="https://github.com/Kaeto-nwk/Electronic-Product-Analysis/assets/150389314/55738f90-3f5a-4c19-8792-84ce71c7836e">
</p>


2. Which brand was highly recommended by customers?

Logitech was the most recommended brand and had 950 recommendations. Interestingly even though it was highest recommended it was on the lower end of the average rating in comparison to other brands. It was the brand with the highest number of reviews and just fell short of reaching a rating of 4.00 on average. On the other hand, Sdi Technoligies Inc. was the least recommended company but still had a higher average rating than Logitech. I would have expected to see a more positive relationship between companies that were highly recommended and those that received a high average rating but that is not the case with this there is no distinct relationship.

<p align="center" width="100%">
<img width="700" alt="image" src="https://github.com/Kaeto-nwk/Electronic-Product-Analysis/assets/150389314/0ff88817-426f-449b-a8e1-740a6138474f">
</p>


3. Which brand received the highest rating on average?

The brand with the highest average rating is Clarity-Telecom followed closely by Definitive Technology. Clarity-telecom has a high rating but also has a very low number of reviews. However, majority of the brands received an average rating above 4.00  which is very positive and reflects that customers are highly satisfied with the products received.


<img width="1000" alt="image" src="https://github.com/Kaeto-nwk/Electronic-Product-Analysis/assets/150389314/5d52e02a-b2d9-4a33-9cdd-2feba8828484">



## Recommendations 

1. To improve data quality I suggest guiding the reviews more by providing specific questions that can assess the products better and the customer's experience. This will allow the company to understand which products need improvement and where their customer service excel or could be improved. Also, detailed reviews would encourage more customer engagement with the platform.


## Limitations 

The sample size was a limitation of the data, the lack of variety in the sample skewed a few of the insights. The lack of data availability made some of the data unreliable. For example, the brands which had only 11 reviews but had a 4.91 out of 5  star rating were considered as one of the top products based on average rating whereas a brand that had an average rating of 4.85 from 123 reviews. Although both values are quite similar there is a clear distinction in which ranks higher, therefore, reliability of the data is important as it can be misleading.
An issue I encountered with this limitation was filtering for the number of reviews and deciding what sample size was large enough to be considered reliable. 

Another limitation was that the data didn't have enough depth to explore the insights more deeply to understand what had caused trends or why some brands performed better than others.
