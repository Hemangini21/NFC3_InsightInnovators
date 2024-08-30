# PoliticInsight

## Overview

`politicInsight` is a data-driven project aimed at analyzing and summarizing the parliamentary and constituency work of politicians. Using a dataset collected through web scraping and manual entry, this project performs sentiment analysis and provides insights into the activities and initiatives of various politicians.

## Dataset

The dataset used in this project contains information about different politicians with the following columns:

- **Name**: Name of the politician
- **Title**: Title of the News Article
- **Source**: Source of the information
- **Published At**: Date when the information was published
- **Link**: URL to the source of information
- **Sentiment**: Sentiment analysis result (positive, negative, neutral)
- **Activity**: The politician's parliamantary activity
- **Description**: Description of the activity
- **Unnamed: 0**: Unnamed column 
- **Scheme/Initiative**: Scheme or initiative associated with the activity
- **Description.1**: Additional description related to the scheme/initiative
- **Unnamed: 2**: Another unnamed column (may contain index or redundant information)
- **Name**: Name column (to be used as identifier)


## Data Collection

The dataset was assembled through:

1. **Web Scraping**: Automated scripts were used to collect data from various online sources.
2. **Manual Entry**: Some columns were manually filled due to the lack of authentic data available online.

### Limitations

- **Criminal Records**: Information regarding criminal records of politicians could not be included due to the sensitive nature of such data and its limited availability online. These records are often considered controversial and not readily accessible.

## Analysis

The project performs the following analyses:

- **Sentiment Analysis**: Evaluates the sentiment expressed in the politician's activities and initiatives from news articles.
- **Summary of Parliamentary Work**: Provides a summarized view of the politician's contributions and work in the parliament.
- **Summary of Constituency Work**: Offers insights into the politician's activities and initiatives in their respective constituencies.

## Advantages

1. **Enhanced Transparency:**
   - Provides a clear and detailed view of politician's parliamentary and constituency work, promoting accountability.

2. **Informed Decision-Making:**
   - Helps citizens make informed choices by summarizing and analyzing politician's activities and public sentiment.

3. **Sentiment Analysis:**
   - Offers insights into public sentiment regarding politician's actions, reflecting the general perception of their work.

4. **Comprehensive Data Collection:**
   - Combines web scraping with manual data entry to create a more complete dataset, reducing data gaps.

5. **Customizable Reports:**
   - Enables the generation of customized reports and summaries based on specific criteria, such as individual politicians or time periods.
  
   **Streamlit App :**[Link Text](https://nfc3insightinnovators.streamlit.app/)



