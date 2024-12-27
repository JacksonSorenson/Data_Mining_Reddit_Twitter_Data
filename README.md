**Research Project: Social Media Tobacco Content Analysis**


**Project Overview**

This project explores the exposure and engagement of young adults with tobacco-related content on social media platforms, including Reddit, X (formerly Twitter), Instagram, and YouTube. The study focuses on determining the feasibility of collecting personal social media handle information from participants in a longitudinal study and scraping publicly accessible social media data to identify tobacco-related content.

**Background**

Exposure to tobacco-related content on social media is associated with an increased risk of tobacco use among young adults. This research aims to evaluate:

The feasibility of collecting personal social media handle information from young adult college students participating in a longitudinal study.

The effectiveness of scraping and classifying tobacco-related data from publicly accessible social media accounts.

**Methods**

**Data Collection**

Participants provided social media handles for YouTube, Instagram, Twitter/X, and Reddit during the second wave (Spring 2024) of a longitudinal study. Handles were manually validated for accuracy and public accessibility. Invalid or blank responses and private accounts were excluded.

**Data Scraping**
The following tools were employed to scrape data:

Reddit: PRAW

Twitter/X: Zeeschuimer

Instagram: Apify

YouTube: Apify and a custom scraper for video transcriptions

**Classification**

The scraped data was processed using ChatGPT 4.0 via Microsoft Copilot to identify posts and comments related to smoking, vaping, THC, CBD, and their combinations.

**Data Overview**

Reddit: 90 users, 6,057 comments, 893 posts

Twitter/X: 98 users, 28,953 posts

Instagram: 253 users, 2,111 posts, 1,381 comments, 815 reels

YouTube: 263 users, 1,000 videos, 314 video transcripts

**Identified Content**
Smoking-related: Reddit (7), Twitter/X (59), Instagram (1), YouTube (10)

Vaping-related: Reddit (2), Twitter/X (12), Instagram (0), YouTube (1)

No posts combining CBD or THC with vaping were identified.

**Results**

The study demonstrates the feasibility of collecting personal social media handle information for longitudinal research and scraping data for analysis. However, due to the small number of identified tobacco-related posts, future research should aim for larger sample sizes to capture more relevant content.

**Implications**

The findings suggest that:

Social media scraping can enhance specificity in analyzing young adult exposure to tobacco-related content.

Recruitment strategies for larger participant samples are essential to improve data relevance.

**Files and Code**

The repository includes the following scripts for data scraping and processing:

YouTube_Video_Transcription_Code.ipynb: Custom scraper for video transcriptions.

Selenium.ipynb: Automation scripts for Instagram scraping.

Raw_Commets_Code.ipynb: Extracts raw comments from various platforms.

Comment_Keyword_Filtered_Code.ipynb: Filters comments based on keywords.

Raw_Posts_Code.ipynb: Extracts raw posts.

Post_Keyword_Filtered_Code.ipynb: Filters posts using keyword matching.

**Conclusion**

This project highlights the potential of leveraging social media data for research on tobacco use. It emphasizes the need for continued refinement in participant recruitment and data collection methods to improve study outcomes.
