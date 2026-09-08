# Video Game Sales Analysis

Exploratory data analysis of historical video game sales using **Python, pandas, and Matplotlib**.

The goal of this project was to practice an end-to-end data analysis workflow: inspecting and cleaning a raw dataset, exploring sales patterns, creating visualizations, and communicating meaningful findings while accounting for missing data and sample-size limitations.

## Dataset

The dataset comes from the **Maven Analytics Data Playground** and contains video game sales data across different consoles, genres, publishers, regions, and release years.

The main dataset contains:

- **64,016 records**
- **14 original columns**
- Game and platform information
- Genre, publisher, and developer
- Critic scores
- Global and regional sales
- Release dates

Sales values are reported in **millions of units**.

A significant portion of the sales and critic-score data is missing, so results in this analysis represent the available recorded data rather than the complete video game market.

## Tools & Skills

- **Python**
- **pandas**
- **Matplotlib**
- **Jupyter Notebook**
- Data cleaning and type conversion
- Missing-value analysis
- Grouping and aggregation
- Filtering and sorting
- Data normalization
- Exploratory data analysis
- Data visualization
- Correlation analysis

## Questions Explored

1. How has the number of game releases changed over time?
2. Which genres have the highest total sales?
3. Which platforms have generated the highest sales?
4. Which publishers have generated the highest sales?
5. How do gaming preferences differ between North America, Japan, and PAL regions?
6. Which game titles have the highest combined recorded sales?
7. Is critic score associated with higher game sales?

## Limitations

Several limitations should be considered when interpreting the results:

- `total_sales` is missing for a large portion of the dataset.
- Critic scores are available for only a relatively small subset of games.
- Regional sales columns also contain substantial missing data.
- Recent release years may have incomplete coverage.
- Publisher names may contain naming variations or related labels listed separately.
- Rankings based on averages can be misleading when only a small number of observations are available.

Minimum sample-size thresholds were therefore used for some comparisons to reduce misleading results.

## Repository Structure

```text
video-game-sales-analytics/
│
├── data/
│   ├── vgchartz-2024.csv
│   └── vg_data_dictionary.csv
│
├── analysis.ipynb
├── README.md
└── .gitignore
```

## Full Analysis

The complete analysis, including data exploration, transformations, calculations, visualizations, and interpretation, is available in:

**[`analysis.ipynb`](analysis.ipynb)**

## What I Learned

This project helped me practice moving beyond simply writing pandas commands and thinking more carefully about what the data actually supports.

In particular, I learned to:

- distinguish between total and average performance
- consider sample size before interpreting averages
- handle missing data differently depending on the analytical question
- distinguish correlation from causation
- communicate limitations alongside results

---

*This project was created as part of my data analytics portfolio.*
