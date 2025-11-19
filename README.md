🎬 Netflix Data Analysis – Python | Pandas | Visualization

A complete exploratory data analysis (EDA) project based on Netflix viewing history. This project demonstrates data cleaning, manipulation, feature extraction, and visualization techniques using Python data science libraries.

🔥 Features

Loads and reads the Netflix viewing history CSV

Converts the Date column into the correct datetime format

Shows the first few rows and dataset info

Counts total titles watched

Finds how many unique titles you watched

Shows your most-watched movie/show

Creates basic charts using Matplotlib

Displays stats like rewatched titles

Handles cases where there are no rewatched movies

Basic data cleaning and formatting

🧰 Tech Stack

Python

Pandas

NumPy

Matplotlib

Seaborn

📁 Project Structure

netflix-data-analysis/

│── data/

│     └── netflix_history.csv

│── notebooks/

│     └── analysis.ipynb

│── visualizations/

│     └── charts.png

│── README.md


🧹 Data Cleaning Steps

Removed duplicates & missing values

Converted date columns to datetime format

Extracted:

watch hour

day of week

duration

category (movie/series)

Handled inconsistent genre labels

📊 Visualizations

Genre distribution (Pie chart)

Daily watch trend (Line chart)

Hourly activity heatmap

Top watched shows (Bar chart)

Watch time comparison

▶️ How to Run

Install dependencies

pip install pandas matplotlib seaborn numpy

Launch the notebook

jupyter notebook analysis.ipynb

📸 Screenshots

## 📸 Visualizations

![Netflix Analysis Screenshot 1](https://github.com/user-attachments/assets/faaf8566-9a77-4def-9cab-8fc0bc57f8e1)

![Netflix Analysis Screenshot 2](https://github.com/user-attachments/assets/f2918e3a-37ae-42ea-ba3b-05d5a930ef73)



🚀 Future Enhancements

Add more charts (pie chart of genres, bar chart of watch frequency by year/month)

Add a heatmap showing what days you watch the most

Add top 10 most-watched shows/movies

Add total minutes watched (if data has duration)

Add filtering options (only movies, only TV shows, specific years)

Improve visual design of graphs (colors, labels, styling)

Create a dashboard using Streamlit or Plotly

Add recommendations (e.g., genres you watch most)

Clean the data more (remove duplicates, fix inconsistent titles)

Add a summary report at the end

📄 License

Open-source — for educational use.
