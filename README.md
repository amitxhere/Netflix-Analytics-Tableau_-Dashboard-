# 📺 Netflix Movies & TV Shows Dashboard (Tableau Project)

This project is an interactive Tableau dashboard that provides detailed insights into the distribution, ratings, genres, and trends of Netflix content, including movies and TV shows.

It allows users to explore Netflix's global content offerings with visualizations by country, rating, genre, year, and more.

---

## 📊 Dashboard Overview

The dashboard includes the following components:

### 1. 🌍 **Total Movies & TV Shows by Country**
- **Map View** showing content production by country.
- The **United States** has the highest number of entries (2,032), followed by **India**, **United Kingdom**, etc.
- Color intensity represents content volume.

### 2. 🔠 **Ratings Distribution**
- Bar chart visualizing content count per rating category.
- Top ratings include:
  - **TV-MA**: 2,027 titles
  - **TV-14**: 1,698 titles
  - **TV-PG**: 701 titles
  - Other categories include PG, R, G, NR, TV-Y, etc.

### 3. 🍿 **Movies vs TV Shows Distribution**
- Donut chart showing:
  - **Movies**: 4,265 titles (68.42%)
  - **TV Shows**: 1,969 titles (31.58%)

### 4. 📅 **Total Movies & TV Shows by Year**
- Area chart showing the growth of Netflix’s library from 2008 to 2020.
- Rapid increase from 2015 onwards.
- Peaks around 2018–2019.

### 5. 🏷️ **Top 10 Genres**
- Horizontal bar chart with most frequent genre combinations:
  - Documentaries (299)
  - Stand-Up Comedy (273)
  - Dramas, International Movies (248)
  - Others include Kids' TV, Comedies, Independent Movies, etc.

### 6. 🎛️ **Dynamic Filters**
- **Type**: Movie / TV Show
- **Title**: Select specific title (2,215+ available)
- **Ratings**, **Release Year**, **Duration**, **Date Added**
- **Genre**: Filter to specific genres such as Documentaries, Sports Movies, International, etc.

---

## 📂 Dataset Information

- **Source**: Netflix dataset (commonly found on Kaggle or similar platforms)
- **Number of records**: ~6,234 (4,265 movies + 1,969 TV shows)
- **Fields Used**:
  - Title
  - Type (Movie / TV Show)
  - Country
  - Genre(s)
  - Duration
  - Rating
  - Release Year
  - Date Added
  - Description

Sample description shown in dashboard:
> *"This intimate documentary follows rock star Artiwara Kongmalai on his historic, 2,215-kilometer charity run across Thailand in 2017."*

---

## 🛠️ Tools Used

- **Tableau Public (Desktop Edition)**
- **Data Cleaning**: (e.g., Microsoft Excel )
- **Visualization**: Tableau Dashboards, Filters, Maps, and Charts

---

## 🚀 Getting Started

### To View the Dashboard:
1. Open `Netflix_Dashboard.twbx` using [Tableau Public](https://public.tableau.com/s/download).
2. Interact with the filters to explore the data.
3. View trends by selecting different release years, ratings, or genres.

### Requirements:
- Tableau Public (Free)
- Dataset in `.csv` format .

---

## 📁 Repository Contents

| File / Folder              | Description                                 |
|---------------------------|---------------------------------------------|
| `Netflix_Dashboard.twbx`  | Tableau Workbook file (Packaged)            |
| `README.md`               | Project documentation (you are reading it)  |
| `dashboard_screenshot.png`| Image of the final dashboard (uploaded)     |


---

## 📈 Potential Improvements

- Include more granular date filters (e.g., by month)
- Add language breakdown or subtitles availability
- Integrate with IMDb or Rotten Tomatoes scores
- Track removals/additions over time

---

## 📜 License

This project is released under the **MIT License**. You are free to use, share, and modify it with attribution.

---

## 🙏 Acknowledgments

- Netflix for inspiring the project.
- Open-source data communities like **Kaggle**.
- Tableau for powerful visualization tools.

---

<img width="1899" height="1045" alt="image" src="https://github.com/user-attachments/assets/b341e66c-29da-4c87-b6fc-012c5a32c436" />


