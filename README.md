# Video Game Sales and Ratings Dataset

## Overview

The Video Game Sales and Ratings Dataset is a comprehensive collection of data points providing insights into the video game industry. Aimed at supporting data-driven decision-making, this dataset is a valuable resource for game developers, publishers, critics, and researchers interested in understanding trends and patterns within the gaming domain.

## Key Features

- **Wide Range of Variables:** The dataset covers a broad spectrum of variables including platform availability, genre classification, publishing entities, developers, and sales figures across various regions (North America, Europe, Japan, Other regions).
  
- **Sales Information:** Detailed sales information for different regions (NA, EU, JP, Other, Global) allows for regional market analyses and global performance comparisons.

- **User and Critic Reviews:** Both critic reviews and user ratings are included, providing a comprehensive view of a game's market reception and perceptual quality from both expert critics and the gaming community.

- **Temporal Insight:** The 'Year_of_Release' column offers temporal insights, allowing for trend analysis and temporal pattern identification.

- **Community Engagement:** 'User_Count' provides information about community engagement levels, complementing traditional sales metrics.

- **ESRB Ratings:** The inclusion of the 'Rating' variable offers standards-based categorical information about age-specific content appropriateness.

## How to Use the Dataset

### Getting Started:

- Familiarize yourself with column descriptions to understand the type of data available in the dataset.

### Conceptual Understanding:

- **Platform:** Highlights gaming platforms with optimal sales.
- **Year_of_Release:** Provides insights into gaming market trends and allows for timeline analysis.
- **Genre:** Useful for analyzing popular genres or identifying niche markets.
- **Publisher / Developer:** Monitoring these can reveal industry leaders or developers consistently producing well-received games.
- **Sales Columns (NA_Sales, EU_Sales, JP_Sales, Other_Sales, Global_Sales):** Instrumental for performing regional market analyses, studying global performance indicators, and comparing regional popularity differences.

### Choosing Tasks:

- **Exploratory Data Analysis (EDA):** Identify missing values/nulls, extract meaningful summary statistics.
  
- **Data Visualization:** Generate charts, scatter plots, heat maps to encapsulate sales trends, plot genre popularity over time, or compare user vs critic scores.

- **Predictive Modelling:** Predict future sales figures or game ratings based on features like genre, platform, developer, etc.

- **Ratings & Sales Correlation:** Analyze how a game's ESRB rating impacts its sales and overall reception.

### Research Ideas

1. **Video Game Sales Forecasting:**
   - Forecast global and regional future sales based on genre, platform, publisher, critic scores, and user scores.

2. **Success Predictor Model:**
   - Develop a machine learning model predicting the success of a new video game before release in terms of user score, critic score, or projected sales.

3. **Market Segmentation Analysis:**
   - Provide insights about different market segments within the gaming industry, such as popular genres/platforms in specific regions.

## Acknowledgements

If you use this dataset in your research, please credit the original authors.

## License

See the dataset description for more information.

## Columns

**File:** video_games_sales.csv

| Column Name     | Description                                                        |
| --------------- | ------------------------------------------------------------------ |
| Platform        | The gaming console for which the game was developed. (String)     |
| Year_of_Release | The year when the game was first released. (Integer)               |
| Genre           | The type of the game, such as action, adventure, etc. (String)     |
| Publisher       | The name of the company that published the game. (String)          |
| NA_Sales        | The number of copies of the game sold in North America (in millions). (Float) |
| EU_Sales        | The number of copies of the game sold in Europe (in millions). (Float)      |
| JP_Sales        | The number of copies of the game sold in Japan (in millions). (Float)        |
| Other_Sales     | The number of copies of the game sold in other parts of the world (in millions). (Float) |
| Global_Sales    | The total number of copies of the game sold worldwide (in millions). (Float) |
| Critic_Score    | The average score given to the game by critics. (Float)             |
| Critic_Count    | The number of critics who reviewed the game. (Integer)             |
| User_Score      | The average score given to the game by users. (Float)              |
| User_Count      | The number of users who reviewed the game. (Integer)              |
| Developer       | The company or team that developed the game. (String)             |
| Rating          | The ESRB rating of the game, indicating the appropriate age group for the game. (String) |
