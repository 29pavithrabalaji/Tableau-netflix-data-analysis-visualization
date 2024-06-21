# Tableau-Netflix-Data-Analysis-Visualization

## Netflix Data Analysis Dashboard

### Overview
This project aims to provide an in-depth analysis of Netflix's movie and TV show catalog through an interactive dashboard. The dashboard helps visualize various attributes of the Netflix dataset, including the distribution of content by country, genre, rating, and release year.

### Dataset
The dataset used in this analysis is `netflix_titles.csv`, which includes detailed information about movies and TV shows available on Netflix. Below is a detailed description of the columns in the dataset:

- **show_id**: A unique identifier for each show.
- **type**: Indicates whether the content is a "Movie" or "TV Show".
- **title**: The title of the movie or TV show.
- **director**: Name of the director(s) of the content.
- **cast**: List of main actors/actresses in the content.
- **country**: Country where the content was produced.
- **date_added**: The date the content was added to Netflix.
- **release_year**: The year the content was originally released.
- **rating**: The rating given to the content (e.g., PG, TV-MA).
- **duration**: For movies, this is the duration in minutes; for TV shows, it is the number of seasons.
- **listed_in**: The genres associated with the content.
- **description**: A brief description or synopsis of the content.

### Visualizations

#### 1. Total Movies & Shows by Country
- **Description**: This map visualization shows the distribution of Netflix content across different countries.
- **Details**: Countries are shaded in varying intensities of red to represent the number of shows produced. Darker shades indicate a higher number of shows.

#### 2. Ratings Distribution
- **Description**: A bar chart displaying the count of shows for each rating category.
- **Details**: This chart helps understand the age-appropriateness and content rating distribution of Netflix's catalog. Ratings include TV-MA, TV-14, TV-PG, R, PG-13, PG, etc.

#### 3. Movies & TV Shows Distribution
- **Description**: A bubble chart representing the proportion of movies versus TV shows.
- **Details**: This chart visually compares the number of movies to TV shows in the dataset. The size of the bubbles corresponds to the count of each type.

#### 4. Top 10 Genres
- **Description**: A bar chart showing the top 10 genres by the number of shows.
- **Details**: This chart lists the most popular genres on Netflix, indicating viewer preferences and content diversity.

#### 5. Total Movies & Shows by Year
- **Description**: A bar chart depicting the number of movies and TV shows released each year.
- **Details**: This chart shows trends over time, highlighting periods with significant increases or decreases in content production.

### Instructions for Use

#### Data Loading
1. **Prepare the Dataset**: Ensure the `netflix_titles.csv` file is available in your working directory.
2. **Load the Data**: Use your preferred data analysis tool (e.g., Tableau, Power BI, Python) to load the dataset.

#### Setting Up the Dashboard
1. **Import the Data**: Load the dataset into your tool.
2. **Create Visualizations**: Use the descriptions above to create the visualizations.
   - For the map, use a world map visualization tool and color-code countries based on the count of shows.
   - For bar charts and bubble charts, use standard charting libraries or tools provided by your data analysis software.
3. **Arrange the Dashboard**: Organize the visualizations in a coherent layout that allows for easy interaction and interpretation.

#### Interacting with the Dashboard
1. **Filter Options**: Use filters to narrow down the data by country, genre, rating, and year of release.
2. **Hover and Click**: Interact with the visualizations to get more detailed information (e.g., hover over a country on the map to see the exact number of shows).

### Additional Notes
- **Color Coding**: Movies are typically represented in red, and TV shows in orange to maintain visual consistency.
- **Interactive Features**: Enable interactivity features like tooltips, filters, and drill-downs to enhance the user experience.
- **Data Refresh**: If the dataset is updated, ensure the dashboard reflects the latest data by reloading and refreshing the visualizations.

### Conclusion
This dashboard provides a comprehensive overview of Netflix's catalog, allowing users to quickly understand the composition and distribution of content. By interacting with the visualizations, users can gain valuable insights into the types of content available on Netflix, their geographic distribution, and how they are rated.


