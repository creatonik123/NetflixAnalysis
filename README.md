# Netflix Movie Data Analysis

A comprehensive data analysis project that explores Netflix's movie dataset containing detailed insights about content, ratings, genres, and popularity trends.

## 📊 Project Overview

This project analyzes a dataset of 9,800+ Netflix movies to uncover patterns in content distribution, audience preferences, and rating trends. Through exploratory data analysis and feature engineering, we generate actionable insights about Netflix's content portfolio.

## 🎯 Key Findings

- **Genre Distribution**: Drama dominates with 3,715+ entries, significantly outpacing other genres
- **Rating Patterns**: Vote averages show balanced distribution across 4 rating categories (~2,450-2,467 films per tier)
- **Top Movie**: "Spider-Man: No Way Home" leads with 5,083.95 popularity score (Action, Adventure, Sci-Fi | 8.3 rating)
- **Consistent Quality**: Balanced audience ratings across all time periods demonstrate Netflix's content consistency
- **Content Growth**: Increasing movie releases in recent years with stable average quality ratings

## 📁 Project Structure

```
Netflix-Data-Analysis/
├── README.md                      # Project documentation
├── netflix-data-analysis.ipynb    # Main analysis notebook
├── moviedb.csv                    # Dataset (9,827 movies)
└── requirements.txt               # Python dependencies
```

## 🔍 Analysis Sections

### 1. Data Cleaning & Preprocessing
- Date format conversion (Release_Date → Year)
- Handling null values in Vote_Average
- Removing non-analytical columns
- Genre expansion from comma-separated values

### 2. Feature Engineering
- Vote Average categorization into 4 tiers using quartiles
- Genre conversion to categorical data type
- Popularity score analysis

### 3. Exploratory Data Analysis
- **Genre Distribution**: Frequency analysis of all 19 unique genres
- **Rating Analysis**: Vote average patterns and categorization
- **Popularity Trends**: Highest and top 10 most popular movies
- **Year-wise Analysis**: Movies released and average ratings per year
- **Genre-Rating Correlation**: Average ratings by genre

### 4. Visualizations
- Genre frequency distribution (horizontal bar chart)
- Vote average distribution (histogram + count plot)
- Popularity vs Vote Average (scatter plot)
- Movies per year (line chart with area fill)
- Genre-wise average ratings (horizontal bar chart)

### 5. Key Insights & Summary
- Comprehensive dataset overview
- Top performing genres and movies
- Quality assessment patterns
- Data quality report

## 📊 Dataset Information

| Field | Type | Description |
|-------|------|-------------|
| Title | String | Movie title |
| Release_Date | DateTime | Original release date |
| Genre | String | Movie genres (comma-separated) |
| Popularity | Float | Popularity score |
| Vote_Average | Float | Average IMDb rating (0-10) |
| Vote_Count | Integer | Number of votes received |

**Dataset Stats:**
- Total Records: 9,827 movies
- Total Records (after genre expansion): 25,552 rows
- Unique Genres: 19
- Time Period: Multiple decades of cinema

## 🛠️ Technologies Used

- **Python 3.8+**
- **Pandas**: Data manipulation and cleaning
- **NumPy**: Numerical computations
- **Matplotlib**: Basic visualizations
- **Seaborn**: Advanced statistical visualizations
- **Jupyter Notebook**: Interactive analysis environment

## 📋 Requirements

```
pandas>=1.2.0
numpy>=1.19.0
matplotlib>=3.3.0
seaborn>=0.11.0
```

## 🚀 Getting Started

### 1. Clone the Repository
```bash
git clone https://github.com/creatonik123/Netflix-Data-Analysis.git
cd Netflix-Data-Analysis
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Notebook
```bash
jupyter notebook netflix-data-analysis.ipynb
```

### 4. Execute Cells
- Run cells sequentially from top to bottom
- The notebook will generate visualizations and insights automatically
- Modify dataset path if `moviedb.csv` is located elsewhere

## 📈 Key Metrics

- **Average Movie Rating**: ~6.5/10
- **Total Analysis Period**: 1900s - 2020s
- **Most Common Genre**: Drama (3,715 movies)
- **Data Cleanliness**: 99% (100 null values removed)

## 🎨 Visualizations Generated

1. **Genre Frequency Distribution** - Top 15 genres by count
2. **Rating Category Distribution** - Movies across quality tiers
3. **Vote Average Distribution** - Histogram with mean line
4. **Popularity vs Rating Scatter** - Relationship analysis
5. **Movies Per Year Trend** - Historical release patterns
6. **Genre-wise Average Ratings** - Quality by category

## 💡 Insights & Recommendations

### What We Learned:
✓ Drama is Netflix's content leader
✓ Quality remains consistent across rating tiers
✓ Strong correlation between votes and popularity
✓ Recent years show increased content production
✓ Audience preferences remain stable over time

### Strategic Recommendations:
- Continue investing in Drama genre content
- Maintain quality standards across all content categories
- Use popularity metrics for content acquisition decisions
- Monitor year-on-year trends for market opportunities
- Diversify while leveraging audience preferences

## 📝 Data Processing Workflow

```
Raw Data (9,827 movies)
    ↓
Remove Null Vote_Average (100 rows)
    ↓
Convert Release_Date to Year
    ↓
Drop Non-analytical Columns
    ↓
Categorize Ratings (4 tiers)
    ↓
Expand Genres (9,827 → 25,552 rows)
    ↓
Clean Dataset (9,727 movies)
    ↓
Perform Analysis & Visualization
```

## 📊 Analysis Output

- **Console Output**: Summary statistics and key findings
- **Visualizations**: 6+ high-quality charts and graphs
- **Data Quality Report**: Comprehensive processing summary
- **Insights Report**: Actionable business intelligence

## 📄 License

This project is open source and available under the MIT License.

## 👤 Author

**Nikhat Shaikh**
Data Analyst | AI Automation Enthusiast
[GitHub](https://github.com/creatonik123) | [LinkedIn](https://linkedin.com/in/nikhatfatema)

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs and issues
- Suggest improvements
- Add new analysis sections
- Improve visualizations

## 📧 Contact & Support

For questions, suggestions, or feedback:
- **Email**: sk.nikhatfatema@gmail.com
- **GitHub Issues**: [Open an issue](https://github.com/creatonik123/Netflix-Data-Analysis/issues)
- **LinkedIn**: [Connect with me](https://linkedin.com/in/nikhatfatema)

---

**Last Updated**: February 2025
**Status**: ✅ Active & Maintained
