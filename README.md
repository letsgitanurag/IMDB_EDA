# IMDB Exploratory Data Analysis

## Description
The dataset comprises anonymized data on movies available on IMDb, capturing various aspects such as genre, rating, and revenue. This dataset can be utilized for analyzing movie trends, audience preferences, and the impact of different attributes like genre and director on movie success.

### Key Objectives:
- Analyze trends in movies.
- Understand audience preferences.
- Examine the impact of different attributes on movie success.

### Insights Gained:
- Identify factors contributing to high ratings and box office revenue.
- Gain insights into the popularity of genres over time.
- Analyze relationships between movie features (e.g., genre, director) and metrics like ratings and revenue.
- Explore the popularity of actors and directors.
- Understand critical reception through Metascore.

## Dataset Overview
The dataset contains 1000 rows and 12 columns, with the following features:
- **Rank**: Rank of the movie.
- **Title**: Title of the movie.
- **Genre**: Genre(s) of the movie (multiple genres are separated by commas).
- **Description**: A brief description of the movie.
- **Director**: Director(s) of the movie.
- **Actors**: Leading actors in the movie.
- **Year**: Year of release.
- **Runtime (Minutes)**: Duration of the movie in minutes.
- **Rating**: IMDb rating of the movie.
- **Votes**: Number of votes received on IMDb.
- **Revenue (Millions)**: Revenue generated in millions of dollars (872 non-null entries, indicating some missing values).
- **Metascore**: Metascore rating (936 non-null entries, indicating some missing values).

## Project Workflow
1. **Data Collection**: Load the IMDb dataset.
2. **Data Preprocessing**:
   - Handle missing values.
   - Perform feature extraction.
   - Split data into training and testing sets.
3. **Exploratory Data Analysis (EDA)**:
   - Perform data cleaning and handle missing values.
   - Conduct detailed exploratory analysis and visualizations to gain insights.
4. **Model Development**:
   - Train models like Random Forest and Linear Regression.
   - Evaluate model performance using metrics like Mean Squared Error (MSE).
5. **Hyperparameter Tuning**:
   - Use techniques such as Grid Search or Random Search to find the best hyperparameters for your models.

## Results
- **Random Forest MSE**: 152.26537496338528
- **Linear Regression MSE**: 155.935333079584

### Conclusion
The project provides a comprehensive exploration of the movie dataset, leading to insights into:
- Revenue trends over the years.
- Genre-based and director-specific patterns.
- Relationships between movie runtime, ratings, and revenue.

### Purpose
The purpose of this project is to identify and remove columns from a dataset that have a correlation coefficient above a specified threshold. This is useful in data preprocessing, especially in machine learning, where multicollinearity can negatively impact model performance.

## FAQs
1. **What is the purpose of this project?**
   - The purpose is to analyze movie trends, audience preferences, and the impact of different attributes like genre and director on movie success.

2. **How does this project handle missing values?**
   - Missing values are handled during the data preprocessing step by either imputing or removing them to ensure data quality.

3. **What models are used in this project?**
   - The project utilizes Random Forest and Linear Regression models for predictions and performance evaluation.

4. **How is the performance of the models evaluated?**
   - The performance is evaluated using metrics like Mean Squared Error (MSE).

5. **What is the significance of hyperparameter tuning?**
   - Hyperparameter tuning techniques like Grid Search and Random Search are used to find the best hyperparameters for the models, improving their performance.

## How to Run
1. Clone the repository.
2. Install the required packages.
3. Run the Jupyter notebook.

## Contributing
Feel free to fork this project, open an issue, or submit a pull request with any improvements or additions.


