SWYNEX Task 2: Exploratory Data Analysis (EDA)
Dataset
The cleaned Netflix dataset from my Task 1 — 8,797 rows, 12 columns, 0 missing values.Task 1 repo: [[https://github.com/SHAIK-DEEN-MOHAMMED/SWYNEX-Data-Cleaning-Preparation]

Tools Used
Python (pandas, matplotlib) in Google Colab.

Key Statistics
Content: 6,131 Movies · 2,666 TV Shows
Average movie length: ~100 minutes (shortest 3 min, longest 312 min)
Average release year of content: ~[2014]
7 Insights
1. Movies dominate the catalog
69.7% of all 8,797 titles are Movies; only 30.3% are TV Shows.Movies vs TV Shows

2. Content additions peaked in 2019
Additions grew sharply year after year, peaked in 2019 with 2,016titles added, then dropped — likely due to the 2020 pandemic and anincomplete 2021 in the dataset.Content per year

3. The USA produces the most content
Top 3 countries: United States (2,812), India (972), United Kingdom (418).The USA count is nearly 3× India's.Top countries

4. International Movies is the biggest genre
Top 3 genres: International Movies (2,752), Dramas (2,427), Comedies (1,674).Netflix's catalog is strongly international.Top genres

5. Netflix skews mature — TV-MA is the most common rating
Most titles are rated TV-MA (adult audience), followed by TV-14.Ratings

6. The typical Netflix movie is ~100 minutes
Most movies run between 80–120 minutes. Outliers exist on both ends:a 3-minute short film and a 312-minute (5+ hour) epic.Movie length

7. Anomaly: a 93-year-old film arrived on Netflix
"Pioneers: First Women Filmmakers*" was released in 1925 but added toNetflix in 2018 — a gap of 93 years. Netflix continues adding restoredclassic content decades after release.

Patterns & Anomalies Noticed
Explosive growth 2015–2019, then a sudden decline
Extreme movie lengths on both ends (3 min and 312 min)
Old classics added decades after release (max gap: 93 years)
