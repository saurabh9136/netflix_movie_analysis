# Netflix Movie Analysis Projects
![](https://github.com/najirh/netflix_sql_project/blob/main/logo.png)

## 2. Movie Data Analysis with Pandas & Seaborn
This project explores a dataset containing movie information, including:
- Release dates
- Popularity scores
- Vote counts & averages
- Genres

**Dataset Used:** `mymoviedb.csv`

### **Data Cleaning & Preprocessing:**
- Converted `Release_Date` to year format.
- Removed unnecessary columns (`Overview`, `Original_Language`, `Poster_Url`).
- Categorized `Vote_Average` into four labels: `not_popular`, `below_average`, `average`, `popular`.
- Split and exploded `Genre` values for better analysis.

### **Exploratory Data Analysis (EDA):**
- Identified missing & duplicate values.
- Examined outliers in the `Popularity` column.
- Checked the most frequent movie genres.
- Analyzed trends in movie releases over the years.

### **Visualizations:**
- **Genre Distribution** – Count plot of different genres.
<img width="773" alt="image" src="https://github.com/user-attachments/assets/3e47edf6-f19e-4c7b-a9f0-da9995384528" />

- **Vote_Average Distribution** – Categorized vote analysis.
  <img width="821" alt="image" src="https://github.com/user-attachments/assets/d5ab7900-75c3-4e90-ac55-a37b73f8bf96" />

- **Movie Popularity** – Identified the most & least popular movies.
- **Release Year Trends** – Histogram of movie release years.
<img width="826" alt="image" src="https://github.com/user-attachments/assets/700a45d7-8f30-4ba4-8e00-48de63cbc8b6" />


### **Tech Stack:**
- **Pandas** – Data Cleaning & Transformation
- **NumPy** – Numeric Computation
- **Matplotlib & Seaborn** – Data Visualization

---
This project helps uncover patterns in movie data using Python-based data analysis techniques.
