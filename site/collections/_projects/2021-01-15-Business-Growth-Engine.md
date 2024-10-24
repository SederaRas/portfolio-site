---
_schema: default
date: 2024-08-10 08:20:00 -0400
title: Business Growth Engine
subtitle: Web Scraping - Data Analysis - Data Visualization
image: /uploads/busiiness20growth-2.png
---
[GitHub Repo](https://github.com/SederaRas/Business_Development_Public.git "Github Repo"){: target="_blank" rel="nofollow noopener"}

## Overview

This project was part of a **Business Development** initiative aimed at tapping into the **Saudi Arabian market**. The goal was to build a **growth engine** that would help identify companies hiring data talent, locate key contacts, and forecast opportunities for engagement.

#### Key Milestones

The client outlined several key milestones:

1. Identify companies hiring data talent on **Indeed**.
2. Extract relevant company data and key contacts from **Crunchbase**.
3. Reach out to key contacts via LinkedIn.
4. Profile companies.
5. Predict collaboration opportunities.

My focus was primarily on the first two milestones—finding hiring companies and extracting relevant data within the Saudi Arabian market.

## Workflow & My Contributions

##### **1\. Collecting Job Data:**

* I enhanced existing scripts to scrape job listings from Indeed, improving error handling to keep the process running smoothly even when APIs encountered issues. By switching to ScraperAPI, I managed to overcome technical challenges and ensure continuous data collection.

##### **2\. Processing Data:**

* I developed a Python script to clean and filter the job data, removing irrelevant listings and highlighting key features like essential skills and industry-specific tools. This resulted in a well-organized dataset ready for analysis.

##### **3\. Matching Company Names:**

* Matching company names between Indeed and Crunchbase was a challenge due to inconsistencies. To tackle this, I created a tool using the Rapidfuzz library, which significantly improved the accuracy of name matching and facilitated smooth data integration.

##### **4\. Scraping Company Information:**

* After aligning company names, I refined the scripts for gathering detailed company information and contact details from Crunchbase. I focused on better error handling and data formatting to ensure the information was accurate and ready for analysis.

##### **5\. Creating Dashboard:**

* I built an interactive Tableau dashboard to visualize the job and company data. This tool allowed the client to explore hiring trends, dive into specific details, and identify key contacts. It also provided insights into the most in-demand skills and tools across job roles in Saudi Arabia and North America.

![](/uploads/screenshot-2024-09-12-at-12-01-22-pm-1.png "Dashboard of Saudi Arabia Data jobs")

## Key Insights

From this project, we uncovered several valuable insights:

* **In-demand Skills:** Python, SQL, and cloud technologies (AWS, Azure) are in high demand, with frequent mentions of data analysis, machine learning, and ETL processes.
* **Top Employers:** Major players in the market include *Aramco Services* and *Arabic Computer Systems*.
* **Key Locations:** Riyadh emerged as the top city for data job postings.
* **Strategic Impact:** The findings suggest focusing on high-demand roles like *Data Analyst* and Machine Learning Engineer, and exploring potential collaborations with identified companies.

## Impact

While my role was concentrated on the initial stages, my contributions were crucial in setting up the client’s growth engine. By meticulously creating the tools to collect, process, and match data, I provided a solid foundation for future automation and integration. The insights from the Tableau dashboard enabled the client to strategically plan their engagements and refine their business development efforts.

&nbsp;

#### Skills and Tools Used

* ***Web Scraping & APIs*****\:** ScraperAPI, Scrapfly
* ***Data Processing*****\:** Python (Pandas, NumPy)
* ***NLP*****\:** Rapidfuzz Library
* ***Data Visualization*****\:** Tableau
* ***Other Tools*****\:** VSCode