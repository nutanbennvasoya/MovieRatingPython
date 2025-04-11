# 🎬 Movie Data Analysis Project

This project involves analyzing a movie dataset using Python and libraries such as Pandas, Matplotlib, and Seaborn. The goal is to clean, transform, and extract insights from the data related to movie ratings, revenue, genres, and more.

---

## 📌 Project Tasks

### ✅ Task 1: Reading and Inspection
- Load the movie dataset using pandas
- Inspect the structure and null values

### ✅ Task 2: Data Cleaning
- Drop unnecessary columns
- Remove rows with high percentage of null values
- Fill missing values (e.g., language with 'English')
- Check the percentage of rows retained
- Remove duplicates

### ✅ Task 3: Feature Engineering
- Convert `gross` and `budget` from $ to million $
- Create a new column `profit` = `gross - budget`
- Add a `decade` column from `title_year`
- Extract first 2 or 3 genres from `genres` column into new columns
- Create a ranking column for IMDb Top 250 movies

### ✅ Task 4: Grouping and Aggregation
- Group by `director_name` to find top 10 directors based on average IMDb score
- Group by genre combinations
- Group by actors for review analysis

### ✅ Task 5: Visualization
- Bar chart of average IMDb score by genre
- Scatter plot for `profit` vs `budget`
- Count plot of movies per decade


## 📈 Tools & Libraries Used
- Python
- pandas
- matplotlib
- seaborn
- Jupyter Notebook
