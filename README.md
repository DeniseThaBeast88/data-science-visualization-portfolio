# Data Science and Visualization Portfolio

Twenty Jupyter notebooks from the Data Science course in the Computer Science Graduate Program at Full Sail University, completed by Margaret Gonzalez in September and October 2026. The work moves from Python fundamentals and data preparation to exploratory analysis, text mining, and static, interactive, and three-dimensional visualization.

Notebooks marked **Peer review** respond to a classmate's posted analysis: they verify the classmate's data, reproduce or extend the charts, and explain what the results show. Classmate names have been removed.

## Skills demonstrated

| Area | Tools |
|---|---|
| Data loading and cleaning | pandas, NumPy, openpyxl, python-docx, requests, BeautifulSoup, pypdf |
| Exploratory analysis | descriptive statistics, correlation, group comparisons, IQR outlier removal, missing-data analysis (missingno) |
| Static visualization | Matplotlib, Seaborn (letter value, violin, KDE, heatmap), Squarify tree maps, mplot3d |
| Interactive visualization | Plotly, Bokeh (sliders, range sliders, linked widgets), ipywidgets, ipympl |
| Text analysis | NLTK tokenization and stop words, unigram and bigram frequency, word clouds with custom masks |

## Notebooks

| # | Project | Data | Highlights |
|---|---|---|---|
| 01 | [Python Refresher](01-python-refresher/) | Arithmetic exercises | Operators, type conversion, rounding, and the math module |
| 02 | [Exploring and Preparing Data](02-exploring-and-preparing-data/) | Movies and shows on five streaming services | Cleaning, filtering, type conversion, summary charts |
| 03 | [Netflix Churn Data Deep Dive](03-peer-review-netflix-churn-data-deep-dive/) (Peer review) | Netflix customer churn | Found churn drivers missed by `corr()`; multi-variable filter, new column, IQR outliers |
| 04 | [EDA Visualizations](04-eda-visualizations-chicago-taxi/) | Chicago taxi trips, June 2026 (Chicago Data Portal) | Letter value plot, histogram with KDE, scatter plot |
| 05 | [Video Game Sales](05-peer-review-video-game-sales/) (Peer review) | Video game sales and ratings (Kaggle) | Missing-data bias check, reproduced charts, dual-axis Plotly chart |
| 06 | [NIST AI RMF Text Analysis](06-nist-ai-rmf-text-analysis/) | NIST AI 100-1 (PDF) | PDF text extraction, cleaning, unigram and bigram frequency |
| 07 | [Beyond CSV and Excel](07-beyond-csv-and-excel/) | Word document, HTML web page, Excel workbook | Reading non-CSV sources, word cloud |
| 08 | [NIST Word Cloud](08-peer-review-nist-word-cloud/) (Peer review) | NIST AI 100-1 | Shaped word cloud with rank-based colors |
| 09 | [Visual Analysis with Plotly](09-visual-analysis-plotly/) | Metacritic video games (Kaggle) | Interactive histogram, box plot, and scatter plot |
| 10 | [Extreme Makeover: Graph Edition](10-extreme-makeover-graph-edition/) | U.S. housing and construction indicators (FRED) | Annotated line and scatter plots of lumber prices, mortgage rates, and housing starts |
| 11 | [Creating Visualizations](11-creating-visualizations/) | Steam games, CO2 emissions 1990 to 2024 | Figure and axes control, subplots, styling |
| 12 | [Diabetes Chart Makeover](12-peer-review-extreme-makeover-diabetes/) (Peer review) | scikit-learn diabetes data | Converted standardized values back to real units, added clinical BMI bands |
| 13 | [Seaborn and Squarify](13-joys-of-seaborn-and-squarify/) | Graduates, theme parks, film genres | Heatmap, violin plot, tree map |
| 14 | [Creating More Visualizations](14-creating-more-visualizations/) | Orlando police crimes, data science salaries, YouTube, U.S. electricity | Larger data sets, Seaborn and Squarify |
| 15 | [Interactive Bokeh Scatter Plot](15-bokeh-interactive-chick-fil-a/) | Chick-fil-A nutrition | Calories versus protein with slider and range-slider filters (open `chickfila_bokeh_scatter.html`) |
| 16 | [The Visualizations Continue](16-the-visualizations-continue/) | Songs, GDP growth, Google Play apps, YouTube | Bokeh and ipywidgets dashboards |
| 17 | [Bokeh Scatter Plot](17-bokeh-scatter-plot-movies/) | Movies | Bokeh scatter plot of domestic versus worldwide gross, filtered by genre with ipywidgets |
| 18 | [3D Scatter Plot](18-3d-scatter-world-bank/) | World Bank life expectancy, fertility, and internet use, 2023 | Three-variable scatter in mplot3d with labeled extremes |
| 19 | [More Visualizations, Yes Please](19-more-visualizations-yes-please/) | Steam games, electricity mix 2025 | 3D bar, surface, and scatter plots with ipympl rotation |
| 20 | [2D Views of a 3D Scatter Plot](20-peer-review-2d-vehicle-performance/) (Peer review) | Auto MPG (UCI, Kaggle) | Three linked 2D scatter plots with a shared color scale |

## Run the notebooks

```
pip install pandas numpy matplotlib seaborn plotly bokeh squarify wordcloud nltk pypdf openpyxl python-docx beautifulsoup4 lxml missingno ipywidgets ipympl jupyter
jupyter notebook
```

Each notebook loads its data with a relative path, so open it from inside its own folder. Notebook 07 also expects `harry_potter.docx` (the full book text from Kaggle), which is not included here for copyright reasons.
