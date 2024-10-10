# SpaceX Launch Data Analysis and Prediction

## Project Overview
This project aims to collect, clean, analyze, and predict outcomes for SpaceX's Falcon 9 and Falcon Heavy rocket launches. The project is divided into several key stages, each focusing on a different aspect of the data pipeline—from data scraping to machine learning predictions.

By combining web scraping, SQL, data analysis, and machine learning, the project provides insights into SpaceX's launch history and predicts future booster landing success. Visualizations further enhance the understanding of the data, providing a clear view of trends and patterns in rocket launches.

## Project Components

### 1. Web Scraping (SpaceX-Web-Scraping.ipynb)
- **Objective**: Automatically collect launch data for SpaceX Falcon 9 and Falcon Heavy rockets from a Wikipedia page.
- **Tools Used**: Python, BeautifulSoup for web scraping, Pandas for data processing.
- **Key Features**:
  - Extracts details such as launch date, payload mass, orbit type, and booster landing outcomes.
  - Outputs a structured dataset for further analysis.

### 2. Data Cleaning and Feature Engineering (SpaceX-Data-Collection.ipynb)
- **Objective**: Clean and prepare the scraped data for analysis and machine learning models.
- **Tools Used**: Python, Pandas, NumPy.
- **Key Features**:
  - Handles missing data, normalizes date formats, and cleans payload mass entries.
  - Adds engineered features like payload categories and booster version classifications.
  - Prepares the data for EDA and machine learning.

### 3. Exploratory Data Analysis (EDA) (SpaceX-EDA.ipynb)
- **Objective**: Explore the cleaned SpaceX launch data to uncover trends and insights.
- **Tools Used**: Python, Pandas, Matplotlib, Seaborn.
- **Key Features**:
  - Visualizes relationships between launch features (e.g., payload mass, orbit type) and booster landing success.
  - Generates heatmaps, bar charts, and scatter plots to highlight key patterns.
  - Investigates outliers and trends in launch success over time.

### 4. SQL-Based EDA (SpaceX-EDA-With-SQL.ipynb)
- **Objective**: Analyze SpaceX launch data using SQL queries to provide deeper insights into patterns in the data.
- **Tools Used**: SQL, SQLite, Pandas.
- **Key Features**:
  - Queries the launch data directly using SQL.
  - Performs grouping, filtering, and summarization of launch data to generate insights like launch site performance and booster version success rates.

### 5. Data Visualization (SpaceX-Visualization.ipynb)
- **Objective**: Provide a comprehensive visual analysis of the SpaceX launch data.
- **Tools Used**: Matplotlib, Seaborn, Plotly.
- **Key Features**:
  - Creates detailed visualizations such as time series of launch success, payload mass trends, and booster landing outcomes.
  - Provides interactive plots that allow users to explore data relationships dynamically.

### 6. Machine Learning Prediction (SpaceX-Machine-Learning-Prediction.ipynb)
- **Objective**: Build a machine learning model to predict booster landing success based on launch data.
- **Tools Used**: Python, Scikit-learn, Pandas, NumPy.
- **Key Features**:
  - Trains a classification model (e.g., logistic regression, decision tree) to predict the outcome of booster landings.
  - Uses features like payload mass, orbit type, and booster version to predict the landing success.
  - Evaluates model performance using accuracy, precision, recall, and confusion matrices.

