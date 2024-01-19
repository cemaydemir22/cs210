# Analysis of My Youtube Data

## Description
This project is the project of the CS210 course at Sabancı University. The project is about analyzing my own Youtube data.

## Table of Contents

1. [Motivation](#motivation)
2. [Data Source](#data-source)
3. [Data Analysis](#data-analysis)
4. [Findings](#results)
5. [Limitations](#limitations)
6. [Future Work](#future)



## Motivation<a name="motivation"></a>

As a regular YouTube user, I was inspired for this project by my personal experience of spending a significant amount of time on the platform. YouTube has become an integral part of my daily routine; It serves as a versatile tool for a variety of activities, including listening to music and enhancing my learning experience by accessing educational content.

The decision to analyze YouTube data is related with my desire to understand more deeply how I allocate my time on the platform. Realizing the impact this was having on my daily life, I sought to discover and uncover patterns in the data that could provide insights into my usage habits.

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
  - Presented the confusion matrix for machine learning model.

## Findings<a name="results"></a>

### Hypothesis Testing Results

The chi-square test conducted to evaluate the relationship between months and YouTube usage provided compelling evidence to reject the null hypothesis. This indicates a significant relationship between the time spent on YouTube and the different months.

### Monthly Patterns

Visualizations further illuminated the nuances of YouTube usage across different months:

- **Seasonal Trends:**
  - Noticed distinct patterns in usage across various months, with notable increases in certain periods.
  

- **Time-of-Day Preferences:**
  - Identified a concentration of YouTube usage primarily between 15:00 and 20:00, suggesting a peak activity period.
  
- **End-of-Month Surge:**
  - Observed a consistent increase in YouTube usage towards the end of each month, indicating a temporal trend in user behavior.

### Temporal Analysis

- **Hourly Distribution:**
  - Bar charts and time series analyses highlighted the distribution of YouTube usage throughout different hours.
  

### Machine Learning Model Predictions

- **Decision Tree and Linear Regression:**
  - The machine learning models, including decision tree and linear regression, provided additional insights into predictive patterns.
  

### Visual Representation

- **Charts and Graphs:**
  - Seaborn and Matplotlib visualizations effectively communicated the relationships and patterns uncovered during the analysis.
  

### Conclusion

The findings from this analysis provide a comprehensive understanding of YouTube usage patterns, emphasizing the impact of temporal factors, including months and hours. The rejection of the null hypothesis underscores the significance of temporal trends in influencing individual behaviors on the platform. These insights pave the way for deeper discussions on user engagement, content consumption preferences, and potential avenues for future research.













## Limitations<a name="limitations"></a>

## Limitations

### Data Limitations

1. **Insufficient Information:**
   - The dataset obtained through Google Takeout lacked certain crucial details, such as average time information. This limitation hindered a more comprehensive analysis of YouTube usage patterns.

2. **Missing Values:**
   - Several columns, aside from the 'time' column, contained a significant number of missing values. Notably, the absence of data in certain fields limited the depth and accuracy of the analysis.

### Knowledge Limitations

1. **Analytical Skills:**
   - Limited knowledge in certain analytical techniques may have influenced the depth of the conclusions drawn from the analysis. Further expertise in specific statistical methods or machine learning algorithms could enhance the project's overall robustness.

2. **Interpretation Challenges:**
   - Interpretation of results may be subject to the analyst's understanding of the domain. The complexity of YouTube usage patterns may require additional domain-specific knowledge for more accurate insights.

### Privacy Concerns

1. **Limited Data Sharing:**
   - Due to the private nature of the data, there were constraints on sharing detailed information, potentially impacting the overall quality of the analysis. This privacy consideration limited the extent to which certain findings and patterns could be shared.



## Future Work<a name="future"></a>

### Website Development

1. **Creation of a Website:**
   - Due to time constraints, the project did not include the development of a dedicated website. Future work could involve building a website to showcase the analysis, visualizations, and findings. This would enhance accessibility and provide a more interactive platform for users to explore the insights.

### Data Analysis Enhancements

1. **Inclusion of Average Video Time:**
   - A future iteration of the analysis could incorporate information on the average duration of videos. This additional parameter would offer a more nuanced understanding of time spent on YouTube, considering variations in video length.

2. **Header Analysis:**
   - Exploring the impact of video titles and headers on user engagement could provide valuable insights. Future work might involve analyzing patterns related to specific video titles, assessing their influence on watch times, and uncovering potential correlations.

### Learning and Skill Development

1. **Skill Enhancement:**
   - Invest time in expanding knowledge and skills related to statistical methods and machine learning algorithms. This would contribute to a more sophisticated and comprehensive analysis, potentially uncovering deeper insights.

### Privacy Considerations

1. **Ethical Data Handling:**
   - Further explore methods for ethical data handling, considering privacy concerns. This could involve anonymization techniques or exploring ways to share insights while preserving user privacy.

### Conclusion

The outlined future work provides a roadmap for extending the current analysis. Building a website not only enhances the project's presentation but also contributes to skill development. Analyzing average video time and investigating the impact of headers adds layers of complexity to the exploration of YouTube usage patterns.

