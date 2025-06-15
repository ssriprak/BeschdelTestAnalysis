# 🎬 Bechdel Test Movie Analysis

This project uses the **Bechdel Test** as a metric to analyze thousands of films and evaluate gender representation trends in cinema. It also examines how Bechdel Test scores correlate with box office performance and crew composition.

---

## 📌 What is the Bechdel Test?

A movie passes the **Bechdel Test** if:
1. It has at least two named women,
2. Who talk to each other,
3. About something other than a man.

Scores range from **0 (fail all)** to **3 (pass all criteria)**.

---

## 📁 Project Structure

| Notebook | Description |
|----------|-------------|
| `Beschdel Test Web scraping.ipynb` | Scrapes Bechdel Test scores and metadata for thousands of movies from [bechdeltest.com](https://bechdeltest.com). |
| `Imdb Webscraping BoxOffice.ipynb` | Scrapes IMDb box office and budget data for matching movies. |
| `Analyze_Credits_bechsdel.ipynb` | Parses and analyzes movie cast and crew credits to assess gender representation behind the camera. |
| `Beschdel Test and Box Office.ipynb` | Merges Bechdel scores with box office and budget data to study trends and correlations. |
| `Final Beschdel Test Data.ipynb` | Cleans, merges, and finalizes the dataset for analysis and visualization. |

---

## 📊 Key Features

- ✅ Scrapes and compiles data from **multiple sources**
- ✅ Normalizes and matches movies across datasets using fuzzy matching
- ✅ Computes Bechdel Test results distribution by year, genre, and budget
- ✅ Analyzes **cast/crew gender ratios** using IMDb data
- ✅ Visualizes **trends** over time and the relationship between Bechdel scores and box office revenue

---

## 🔧 Technologies Used

- Python (BeautifulSoup, Pandas, NumPy, FuzzyWuzzy)
- Jupyter Notebooks
- Matplotlib / Seaborn
- IMDb & Bechdel Test Web Scraping

---

## 🧪 Sample Insights (Possible Findings)

- Movies with high Bechdel scores are underrepresented among top-grossing films.
- Female-led or gender-balanced crews correlate with better Bechdel Test outcomes.
- Bechdel-passing movies do not consistently outperform others at the box office — but trends may vary by genre and year.

---

## 📂 Output Data

The final output includes a cleaned CSV with:
- Movie title, year
- Bechdel score (0–3)
- Budget, box office gross
- Cast & crew gender stats

---

## 🚀 How to Run

1. Clone the repo and install dependencies:
   ```bash
   pip install pandas beautifulsoup4 fuzzywuzzy matplotlib seaborn
