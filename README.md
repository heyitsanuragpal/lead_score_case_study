# Predicting Consumer Tastes using Web Data Analysis for Gap Inc.

This project explores the effectiveness of data in predicting consumer preferences compared to traditional creative methods. Using advanced web data analytics, we analyzed customer feedback, sentiment from platforms like Reddit, and sales metrics from Google Shopping. Our goal was to understand the digital presence of brands and evaluate how data could influence their strategic direction.

**Project URL:** [[Project URL](https://harshrajjadeja13.wixsite.com/hjadeja/projects/predicting-consumer-tastes-using-web-data-analysis-for-gap-inc.)]

## Table of Contents
- [Overview](#overview)
- [Primary Objective](#primary-objective)
- [Analysis](#analysis)
  - [Qualitative Analysis](#qualitative-analysis)
    - [Customer Feedback Analysis](#customer-feedback-analysis)
    - [Google Trends Analysis](#google-trends-analysis)
    - [Competitor Analysis on Macy’s Website](#competitor-analysis-on-macys-website)
  - [Quantitative Analysis](#quantitative-analysis)
    - [Insights from 3rd Party Trading Channels like Amazon](#insights-from-3rd-party-trading-channels-like-amazon)
    - [Sentiment Analysis of the Customer using Reddit Data](#sentiment-analysis-of-the-customer-using-reddit-data)
    - [Building Regression Model based on Google Shopping](#building-regression-model-based-on-google-shopping)
- [Applications: Role of Big Data in GAP’s Marketing Strategy](#applications-role-of-big-data-in-gaps-marketing-strategy)
- [Conclusion](#conclusion)

## Overview

In the evolving landscape of fashion retail, the balance between artistic intuition and data-driven decision-making is becoming increasingly critical. Traditionally, the fashion sector has relied on the creative insight of designers to predict trends. Yet, the rise of big data is challenging this norm. Gap, a renowned entity in fashion retail, underscored this shift when the then-CEO Art Peck prioritized data-driven strategies over conventional creative direction in 2017.

Our team conducted an in-depth analysis leveraging advanced web data analytics to address the efficacy of data in predicting consumer preferences compared to traditional creative methods. We meticulously examined diverse data sources, from customer feedback to sentiment analysis on platforms like Reddit and sales metrics from Google Shopping. We aimed to comprehensively understand the digital presence of these brands and assess the potential impact of data on their strategic direction.

## Primary Objective

The primary objective is to assess the implications of the then CEO, Peck’s transition to a data-centric strategy. Our project objective broadly expands into the following three aspects:

1. **Tapping into web data to shed light on Gap’s evolving direction:** Capturing insights on contemporary clothing trends and fashion inclinations.
2. **Conducting an in-depth analysis of all three brands of GAP Inc. — Old Navy, Gap, and Banana Republic:** Understanding their digital footprint and the role of big data in their strategies.
3. **Exploring data-driven methods and traditional creative approaches in marketing:** Identifying the most effective strategy for today’s fashion retail scenario.

## Analysis

Our analysis shows that the big data approach has enormous potential to drive GAP’s business ahead of competitors. Below are six methods (3 qualitative & 3 quantitative), where we have worked on live datasets and derived some valuable insights. These methods can be prototype examples of data-driven techniques to understand customer preferences.

### Qualitative Analysis

#### Customer Feedback Analysis
- Collected customer feedback from the website Customer Affairs.
- Utilized the GPT-3.5 model for sentiment analysis to identify popular fashion trends in the feedback.
- Provided Gap with valuable insights into customer preferences to align their clothing offerings with trends.

#### Google Trends Analysis
- Identifying the best keywords that fit into the GAP Inc. category based on GAP’s listing on Amazon.
- Using the identified categories as keywords to collect data from Google Trends.
- Analyzing the four trending parameters: Trending queries, Most searched queries, Most searched topics, and top state searching for keywords.

#### Competitor Analysis on Macy’s Website
- Use Selenium to extract content from competitors’ websites, including paragraphs, headers, links, spans, articles, etc.
- Employed ChatGPT, LLM to analyze the extracted content and provide insights into the latest fashion trends and popular items.

### Quantitative Analysis

#### Insights from 3rd Party Trading Channels like Amazon
- Sales data from the direct partner, Amazon, is extracted to find out the most sold item, category, and how the customer loved the item.
- This Amazon data can also be used in further stages to validate our prediction model to identify trends or customer preference.
- Since Gap’s sales are predominant on Amazon, this data can also be an excellent source to analyze the brand-wise preferences and their strengths for the products listed on Amazon.

#### Sentiment Analysis of the Customer using Reddit Data
- Collect post descriptions from the Reddit “malefashionadvice” subreddit, specifically targeting GAP brands.
- Conduct sentiment analysis using Azure API post assigning scores to specific keywords.
- Aggregate sentiment scores to identify distinct brand-specific trends for each of the three brands.

#### Building Regression Model based on Google Shopping
- This method effectively highlights how factors like price, discount, promotions, number of reviews, store category, seller, and product category influence the product rating.
- This method can also evaluate whether the same big data strategy works for all three GAP brands.

## Applications: Role of Big Data in GAP’s Marketing Strategy

By integrating data-driven insights with existing creative interpretation, Gap can effectively balance the art of emotional connection with customers and the science of precision and efficiency in marketing efforts. Prioritizing a science-based approach rather than just sticking to traditional creative instincts seems advantageous to GAP.

## Conclusion

In summary, the fashion retail industry is evolving, emphasizing the blend of creative intuition and data-driven decision-making. Our analysis explored the data’s effectiveness in predicting consumer preferences versus traditional methods. Key findings highlight leveraging tools like Selenium, ChatGPT, and Pytrends offer valuable insights. Data analysis across these brands underscores the potential of big data strategies.
