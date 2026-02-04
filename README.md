# Instagram Influencers Data Analysis Project

## Project Overview
This project analyzes and predicts insights on Instagram influencers using a dataset containing information on influencer ranking, engagement metrics, followers, likes, and more.

## Features
- Exploratory Data Analysis (EDA)
- Data Cleaning and Preprocessing
- Feature Engineering
- Regression Model to predict Influence Score
- Classification Model for Engagement Rate Categories
- SQL Database Integration
- Data Visualization

## Dataset
The dataset contains 200 top Instagram influencers with 10 attributes:
1. rank
2. channel_info
3. influence_score
4. posts
5. followers
6. avg_likes
7. 60_day_eng_rate
8. new_post_avg_like
9. total_likes
10. country

## Installation
1. Clone the repository
2. Install dependencies: `pip install -r requirements.txt`
3. Set up MySQL database using `sql/database_setup.sql`
4. Run `main.py` or open notebooks in `notebooks/` folder

## Usage
- Run exploratory analysis: `python main.py --mode eda`
- Train regression model: `python main.py --mode regression`
- Train classification model: `python main.py --mode classification`
- Run SQL analysis: `python main.py --mode sql`

## Project Structure
See the folder structure above for details.

## Technologies Used
- Python
- Pandas, NumPy
- Scikit-learn
- Matplotlib, Seaborn
- SQL
- MySQL
- Jupyter Notebooks
