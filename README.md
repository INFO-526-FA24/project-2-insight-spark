<img style="display: block; margin-left: auto;
margin-right: auto" src="https://phoenixmed.arizona.edu/sites/default/files/campus/marcomm/brand/master-logo/2-ua-horizontal/ua_horiz_rgb_4.png"></img>

This project was developed for the course INFO 526 Data Analysis and Visualization instructed by Prof. Anna Leach.

## Team Members
1. Disha
2. Sharan Pazhanivel
3. Rony Macwan
4. Nithin George

## Project Description

This project aims to analyze unemployment trends across the United States from 1976 to 2022, using state-level data to explore how significant economic events like the 2008 financial crisis and the COVID-19 pandemic affected unemployment rates in different states. By employing data visualization techniques such as line plots and animated choropleth maps, as well as statistical methods including regression analysis and clustering, the study will identify trends, highlight regional disparities, and examine factors contributing to resilience or vulnerability in state-level unemployment.

## Project Structure

- **/dataset/**: Contains the raw and processed datasets used for analysis.
- **/output/**: Generated visualizations, including line plots, choropleth maps, and other insights.

## Steps Involved

1. **Data Cleaning and Preprocessing**:
   - Columns were renamed for uniformity, and missing values were handled using appropriate imputation techniques.
2. **Exploratory Data Analysis (EDA)**:
   - Calculated summary statistics and detected outliers to better understand the dataset.
3. **Data Visualization**:
   - Created line plots, animated choropleth maps, and heatmaps to show unemployment trends across states and highlight periods of economic distress.
4. **Statistical Analysis**:
   - **Regression Analysis**: Used to determine correlations between various economic indicators and unemployment rates.
   - **Clustering**: Grouped states with similar unemployment patterns to understand regional similarities.

## How to Run

   Clone the repository:
   ```bash
   git clone [repository_url]
   ```

## Dependencies
- **R version**: 4.1 or above
- **Packages**:
  - `tidyverse` for data manipulation and visualization.
  - `ggplot2` for plotting.
  - `dplyr` for data transformation.
  - `sf` and `gganimate` for choropleth mapping and animations.