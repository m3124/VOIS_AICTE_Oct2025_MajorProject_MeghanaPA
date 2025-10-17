### VOIS_AICTE_Oct2025_MajorProject_MeghanaPA
## 📂 Dataset Description
The dataset used in this analysis is the **Netflix Titles Dataset** (available on [Kaggle](https://www.kaggle.com/shivamb/netflix-shows)).  
It contains detailed information about movies and TV shows available on Netflix, including:  

| Column Name | Description |
|--------------|-------------|
| show_id | Unique ID for every show |
| type | Movie or TV Show |
| title | Name of the Movie/TV Show |
| director | Director of the title |
| cast | Main cast involved |
| country | Country of production |
| date_added | Date the title was added to Netflix |
| release_year | Original release year |
| rating | TV rating |
| duration | Duration (in minutes or number of seasons) |
| listed_in | Genre/category |
| description | Short summary of the title |

## ⚙️ Data Loading & Cleaning
- Replaced blank values with `NaN`  
- Cleaned and standardized column names  
- Extracted **release year** and **duration (in minutes)**  
- Handled missing categorical values such as `Country`, `Rating`, and `Type`  
- Converted categorical names to title case for consistency  

---

## 📊 Visual Analysis
- **Movies vs TV Shows:** Interactive histogram using `Plotly`  
- **Country-wise Analysis:** Distribution of content by region  
- **Yearly Trend Analysis:** How Netflix’s content library has grown over time  
- **Genre Frequency:** Visualization of the most common genres/categories  
- **Ratings & Duration Insights:** Comparison of movie lengths and ratings distribution  

---

## 🛠️ Libraries Used
- **Data Handling:** `pandas`, `numpy`  
- **Visualization:** `matplotlib`, `seaborn`, `plotly.express`, `plotly.graph_objects`  
- **Utilities:** `re` (regular expressions), `google.colab.files` (for uploads)  

---

## ▶️ How to Run
1. Upload the dataset (`netflix_titles.csv`) in Google Colab or Jupyter Notebook.  
2. Run all cells in the `Netflix_Analysis.ipynb` file.  
3. The notebook will generate both **static and interactive visualizations** for analysis. 
