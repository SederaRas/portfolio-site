---
_schema: default
date: 2023-11-18 19:20:00 -0400
title: The Impact of Central Bank Policy Rate on Bond and Stock Investors
subtitle: Data Analysis - Web Scraping
image: /uploads/anne-nygard-tcj6sjtttwi-unsplash.jpg
---
[GitHub Repo](https://github.com/SederaRas/WEB_SCRAPING_PROJECT.git "Github Repo"){: target="_blank" rel="nofollow noopener"}

## Overview

In today’s economic climate, understanding the dynamic interplay between the **central bank’s policy rates**, **short-term benchmark bond yields**, and **stock market index** is essential to grasp how investors operate within financial markets and the impact on the broader economy. This project aims to examine these relationships to provide insights into financial market behavior and economic implications.

## Objectives

* **Examine Policy Rate Effectiveness**: Analyze the impact and effectiveness of central bank policy rates.
* **Assess Time Series Relationships**: Evaluate the relationships between policy rates, bond yields, and stock market index data.
* **Understand Investor Implications**: Explore how these relationships influence investor behavior and the broader economy.

## Data Sources

We gather data through web scraping using Selenium to capture the following time series:

* **Stock Market Index Data**: Daily index data from the [Toronto Stock Exchange (TSX)](https://money.tmx.com/en){: rel="nofollow"}. This data provides insights into stock market performance.
* **Bank of Canada Policy Rates**: [Daily policy rates](https://www.bankofcanada.ca/core-functions/monetary-policy/key-interest-rate/){: rel="nofollow"} from the Bank of Canada’s website. This data provides insights into the performance of the economy over economic cycles.
* **2-Year Benchmark Bond Yields**: [Short-term bond yields](https://www.bankofcanada.ca/rates/interest-rates/canadian-bonds/){: rel="nofollow"} from the Bank of Canada’s website. This information is crucial for understanding the impact of monetary policy on the yield curve.

## Methodology

* **Web Scraping**: Data is collected using Selenium to automate the extraction of relevant information from the specified webpages.
* **Data Analysis**: We analyze the collected data to assess the relationships between policy rates, bond yields, and stock market performance.

## Findings

* **Policy Rate Impact**: The financial market series tend to follow the target policy rate. As rates rise, investors adjust their decisions between stocks and bonds.
* **Correlation Analysis**: The correlation coefficient between the yield curve and the target policy rate was found to be 93%, indicating a strong relationship. In contrast, the correlation between the target policy rate and stock performance was 43%, suggesting a weaker connection. This indicates that bond investors are more sensitive to changes in the policy rate compared to stock investors.
* **Economic Recession**\*\*: During economic downturns, investors prefer Central Bank Open Market Operations (OMO) instruments, leading to a simultaneous negative movement in both the short-term yield curve and the stock index.

[![image](/uploads/picture1.png)](https://private-user-images.githubusercontent.com/144865074/364063225-883d3914-daa8-43d8-80ad-56343f096d3c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MjYwMjgzNjYsIm5iZiI6MTcyNjAyODA2NiwicGF0aCI6Ii8xNDQ4NjUwNzQvMzY0MDYzMjI1LTg4M2QzOTE0LWRhYTgtNDNkOC04MGFkLTU2MzQzZjA5NmQzYy5wbmc_WC1BbXotQWxnb3JpdGhtPUFXUzQtSE1BQy1TSEEyNTYmWC1BbXotQ3JlZGVudGlhbD1BS0lBVkNPRFlMU0E1M1BRSzRaQSUyRjIwMjQwOTExJTJGdXMtZWFzdC0xJTJGczMlMkZhd3M0X3JlcXVlc3QmWC1BbXotRGF0ZT0yMDI0MDkxMVQwNDE0MjZaJlgtQW16LUV4cGlyZXM9MzAwJlgtQW16LVNpZ25hdHVyZT0yODBiZDBmNjgwZGFlN2VmMzgzMTYwYzU0NzRiMTI2OTA5ZDg2MDk2MjA5NDhhODBhMDg5ZjgwMmNmMmFmN2E5JlgtQW16LVNpZ25lZEhlYWRlcnM9aG9zdCZhY3Rvcl9pZD0wJmtleV9pZD0wJnJlcG9faWQ9MCJ9.BhtEIM02Zbn0s745H7UV3YVDtdw25fAX0ZbvSkHW2-I){: target="_blank" rel="noreferrer noopener"}

### Conclusion

This project provides valuable insights into how policy rates, bond yields, and stock market performance interact. By analyzing these relationships, we can better understand investor behavior and its impact on the broader economy.

#### Tools and Technologies

* ***Selenium***: For web scraping and data extraction from webpages.
* **Python**: For data processing and analysis.
* **Pandas**: For data manipulation and analysis.
* **Plotly**: For data visualization.

  &nbsp;