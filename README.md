# Portfolio-live_streaming

# Twitch & Steam Data Analysis

## Project Overview
This project aims to analyze video game performance on Twitch and Steam to help content creators and analysts understand trends in game popularity. By examining key metrics such as player counts, viewer engagement, and game categories, this analysis provides insights into what makes a game successful on these platforms.

## Datasets Used
### 1. Steam Charts Data
**Filename**: `steam_charts_final_clean.csv`
- Contains historical player count data for games on Steam.
- Key Features:
  - `date`: The timestamp for the data point.
  - `game`: The name of the game.
  - `avg_players`: Average number of players during the recorded period.
  - `gain`: The change in player count compared to the previous period.
  - `peak_players`: The highest number of players online at once.
  - `percent_gain`: The percentage change in player count.

### 2. Twitch Global Data
**Filename**: `twitch_global_data_clean.csv`
- Contains statistics on the most-watched games on Twitch.
- Key Features:
  - `date`: The timestamp for the data point.
  - `game`: The name of the game.
  - `avg_viewers`: Average number of viewers for the game.
  - `peak_viewers`: Maximum viewers recorded at one time.
  - `avg_channels`: Average number of Twitch channels streaming the game.
  - `peak_channels`: Maximum concurrent channels streaming the game.
  - `hours_watched`: Total hours watched for the game during the period.
  - `streamer_ratio`: Ratio of streamers to viewers.

## Objectives
1. **Identify the most popular games on Steam and Twitch**:
   - Find games with the highest player counts and peak concurrent viewers.
   - Analyze trends over time to determine growth or decline.

2. **Analyze correlations between Twitch and Steam performance**:
   - Investigate whether Twitch viewership impacts Steam player counts.
   - Determine if certain game genres perform better on one platform versus the other.

3. **Predict future trends using machine learning**:
   - Forecast player and viewer counts based on historical data.
   - Identify factors contributing to game popularity.

## Methods & Tools
- **Data Manipulation**: `pandas`, `numpy`
- **Visualization**: `seaborn`, `matplotlib`, `missingno`
- **Statistical Analysis**: `statsmodels`
- **Machine Learning (if applicable)**: Regression models for forecasting

## Exploratory Data Analysis (EDA)
- Missing value analysis using `missingno`
- Data distribution and outlier detection with visualizations
- Correlation analysis to identify relationships between variables
- Time series analysis of game performance trends

## How to Use This Project
1. Ensure you have Python and Jupyter Notebook installed.
2. Install dependencies using:
   ```bash
   pip install pandas numpy matplotlib seaborn missingno statsmodels
   ```
3. Load the Jupyter Notebook (`04_data_analysis.ipynb`) and run the cells step-by-step.

## Future Work
- Implement advanced machine learning models for more accurate trend forecasting.
- Include sentiment analysis of Twitch chat and Steam reviews.
- Explore additional data sources to enhance insights (e.g., YouTube gaming statistics).

## Author
[Your Name]

## License
This project is licensed under the MIT License.

