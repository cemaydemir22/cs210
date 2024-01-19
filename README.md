# Analysis of My Youtube Data

## Description
This project is the project of the CS210 course at Sabancı University. The project is about analyzing my own Youtube data.

## Table of Contents

1. [Motivation](#motivation)
2. [Data Source](#data-source)
3. [Data Analysis](#data-analysis)
4. [Findings](#results)
5. [Limitations and future work](#limitations)



## Motivation<a name="motivation"></a>

As a regular YouTube user, I was inspired for this project by my personal experience of spending a significant amount of time on the platform. YouTube has become an integral part of my daily routine; It serves as a versatile tool for a variety of activities, including listening to music and enhancing my learning experience by accessing educational content.

The decision to analyze YouTube data stemmed from my desire to understand more deeply how I allocate my time on the platform. Realizing the impact this was having on my daily life, I sought to discover and uncover patterns in the data that could provide insights into my usage habits.

## Data Source<a name="data-source"></a>

For this project, the primary data source is derived from personal YouTube usage. The data was obtained using Google Takeout, a service that allows users to export their Google data. Specifically, I exported my YouTube data in JSON format, encapsulating a comprehensive record of my interactions and activities on the platform.

### Data Collection Process

1. **Google Takeout:**
   - Utilized Google Takeout to request and download my YouTube data export.
   - Chose the JSON format for the export to ensure a structured and readable representation of the data.

2. **Data Conversion with Pandas:**
   - Employed the Pandas library in Python to convert the exported JSON file into a Pandas DataFrame.
   - Leveraged Pandas' data manipulation capabilities to structure the data in a way that facilitates analysis.

### Dataset Details

The resulting dataset ,including but not limited to:
- Details about watched videos
- Watch history
- Time


The dataset's JSON format allows for flexibility in exploration and analysis, enabling a nuanced examination of my YouTube usage patterns. The project aims to uncover insights into preferences, trends, and temporal aspects of interactions with the YouTube platform.

This personal dataset serves as the foundation for the subsequent exploratory data analysis, hypothesis testing, and machine learning models employed in the project.

## Data Analysis<a name="data-analysis"></a>

### Preprocessing

Upon converting the dataset to a DataFrame, the following preprocessing steps were undertaken:

- **Handling Null Values:**
  - Checked for null values in the general dataset.
  - Specifically examined the 'time' column, crucial for the hypothesis testing phase, and confirmed the absence of null values.

### Hypothesis Testing

#### Null Hypothesis:
There is no relationship between months and the time spent on YouTube.

#### Alternative Hypothesis:
There is a significant relationship between months and the time spent on YouTube.

- **Creation of 'Season' Column:**
  - A new column, 'season,' was introduced to investigate the relationship between months and YouTube usage.

- **Exploration of Seasonal Patterns:**
  - Analyzed time spent during different months, focusing on both summer and non-summer periods.
  
- **Statistical Tests:**
  - Employed statistical methods such as Chi-square statistic and t-test to evaluate the null hypothesis.

### Machine Learning Models

- **Decision Tree and Linear Regression:**
  - Applied machine learning models to further explore and predict patterns in YouTube usage.
  
- **Model Evaluation:**
  - Assessed the performance of the models in capturing and predicting time-related patterns.

### Visualization

- **Seaborn and Matplotlib:**
  - Utilized Seaborn and Matplotlib for a comprehensive set of visualizations.
  
- **Bar Charts:**
  - Visualized the distribution of time spent during different hours for both summer and non-summer periods.

- **Time Series Analysis:**
  - Explored temporal patterns using time series visualizations, offering insights into monthly trends.

- **Pie Charts:**
  - Presented a breakdown of time spent on YouTube during different hours, providing a visual summary of usage patterns.

## Findings<a name="results"></a>














## Limitations and future work<a name="limitations"></a>

...








