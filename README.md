# Social Media Sentiment Analysis

This project analyzes and visualizes sentiment patterns in social media data to better understand public opinion and attitudes toward different topics and brands.

## Objective

The goal of this project is to explore sentiment trends in social media posts and identify how opinions vary across topics. The analysis focuses on overall sentiment distribution, topic-based sentiment patterns, and the most discussed topics in the dataset.

## Dataset

The dataset used in this project is:

- `twitter_training.csv`

The dataset contains the following columns:
- **ID** → unique identifier
- **Topic** → topic or brand being discussed
- **Sentiment** → sentiment label
- **Text** → social media post text

## Tools and Libraries

This project was completed using:

- Python
- Pandas
- Matplotlib
- Jupyter Notebook

## Project Workflow

### 1. Data Loading
The dataset was loaded into a pandas DataFrame.

### 2. Data Preparation
The columns were renamed for clarity:
- ID
- Topic
- Sentiment
- Text

Missing values in the `Text` column were checked, and rows with missing text were removed.

### 3. Sentiment Distribution Analysis
The overall number of tweets for each sentiment category was calculated and visualized using a bar chart.

### 4. Topic-Based Sentiment Analysis
A cross-tabulation was created between topics and sentiments to analyze how sentiment varies across different brands/topics.

### 5. Topic Visualizations
Several charts were created to better understand sentiment patterns:
- overall sentiment distribution
- sentiment by top 10 topics
- stacked sentiment by top 10 topics
- top 5 most mentioned topics
- top 5 topics with most positive tweets
- top 5 topics with most negative tweets

## Key Findings

- **Negative sentiment** was the most common in the dataset.
- **Positive sentiment** was the second most common.
- **Neutral sentiment** came after that.
- **Irrelevant sentiment** had the lowest count.
- The most discussed topics included **LeagueOfLegends, MaddenNFL, CallOfDuty, Verizon,** and **TomClancysRainbowSix**.
- **AssassinsCreed** had the highest number of positive tweets.
- **MaddenNFL** had the highest number of negative tweets.

These findings show that public opinion differs across topics and that some brands receive more positive or more negative reactions than others.

## Visualizations Included

The notebook includes the following visualizations:

1. Sentiment Distribution  
2. Sentiment by Top 10 Topics  
3. Stacked Sentiment by Top 10 Topics  
4. Top 5 Most Mentioned Topics  
5. Top 5 Topics with Most Positive Tweets  
6. Top 5 Topics with Most Negative Tweets  

## Conclusion

This analysis showed that sentiment patterns in social media data are not evenly distributed across topics. The visualizations helped identify the overall sentiment trend and showed how public opinion changes depending on the topic being discussed. The project successfully met the objective of analyzing and visualizing sentiment patterns in social media data.

## Project Structure

```bash
.
├── twitter_training.csv
├── PRODIGY_DS_04.ipynb
└── README.md