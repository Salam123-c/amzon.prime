# 📊 Prime Video Content Analytics Dashboard
> An interactive Power BI dashboard uncovering how Prime Video's global content library breaks down by rating, genre, geography, format, and growth over time.

This project turns a raw Prime Video titles dataset into a fully interactive Power BI dashboard — combining data cleaning, DAX-driven KPIs, and multi-dimensional visual analysis (bar charts, pie charts, geo heatmaps, and timeline trends) to answer six core business questions about the platform's content strategy.

---

## 🖼️ Dashboard Preview

<img width="608" alt="Prime Video Dashboard" src="https://github.com/user-attachments/assets/1714cd35-8508-420d-9f17-d7264016c9a3">

📂 [View Raw Dataset](https://github.com/Salam123-c/amzon.prime/blob/main/amazon_prime_titles.csv) · 📊 [View Power BI File](https://github.com/Salam123-c/amzon.prime/blob/main/amazon.info.pbix)

---

## 📌 Business Scenario & Objective

Prime Video's content library spans thousands of titles across genres, ratings, countries, and formats — making it hard to see the platform's content strategy at a glance.

**Goal:** Clean and structure the raw titles dataset, build KPIs answering six key content-strategy questions, and design an interactive dashboard that lets stakeholders slice the library by genre, rating, country, and release year.

---

## ❓ Key Business Questions (KPIs)

| # | Question | What It Reveals |
| :--- | :--- | :--- |
| 1 | What is the total size of Prime Video's content library? | Overall scale — total titles, shows, movies, and directors |
| 2 | What is the distribution of content ratings? | Audience-maturity mix (13+, 16+, ALL, etc.) |
| 3 | Which genres are most prevalent? | Content-strategy focus by genre |
| 4 | What is the geographical spread of content? | Global production diversity |
| 5 | What is the split between movies vs TV shows? | Format strategy |
| 6 | How has the library grown over time? | Expansion trend and momentum |

---

## 📈 Key Findings

| Metric | Value | Insight |
| :--- | :--- | :--- |
| **Total Titles** | 9,655 | Full scale of the Prime Video content library |
| **Unique Titles** | 519 (across 25 total title variants) | Multiple editions/versions exist for some titles |
| **Directors Represented** | 5,771 | Breadth of creative contribution across the catalog |
| **Top Rating Category** | 13+ (2,117 titles) | Platform skews toward teen-and-above audiences |
| **Top Genre** | Drama (986 titles) | Drama is the dominant content pillar, followed by Comedy |
| **Movies vs TV Shows** | 19.18% Movies / 80.82% TV Shows | Strong strategic tilt toward TV series over films |
| **Top Contributing Regions** | North America & Europe | Largest share of content originates from these regions |

> **Key Insight:** With TV shows making up over **80% of the library**, Prime Video's content strategy is clearly weighted toward episodic series rather than films — a signal of investment in long-form audience retention over one-off viewing.

> **Key Insight:** Ratings data shows **13+, 16+, and ALL categories each exceeding 1,200+ titles**, indicating deliberate coverage of both teen and general-audience segments rather than a single target demographic.

---

## ⚙️ Process & Methodology

**1. Data Collection**
Gathered title-level data across ratings, genres, release years, countries, and content type (movie/TV show).

**2. Data Visualization**
- **Bar charts** — ratings and genre distribution
- **Pie charts** — movies vs TV shows split
- **Geo heatmap** — content volume by country
- **Timeline chart** — content release trend by year

**3. Analysis**
Sliced the dataset across genre, country, and content-type dimensions to surface patterns beyond simple totals — e.g. format strategy (movies vs shows) and regional production concentration.

---

## 🚀 Content Growth Trend

> The library shows an **exponential increase in titles since the early 2000s**, reflecting Prime Video's rapid and sustained expansion as it scaled to meet growing global demand.

---

## 🏁 Conclusion

The dashboard gives a comprehensive view of Prime Video's content strategy: a large and fast-growing library, heavily weighted toward **Drama** and **TV shows**, with production diversity spanning multiple global regions. The steady rise in titles since 2000 signals an actively expanding platform adapting to evolving audience preferences.

---

## 📁 Repository Files

* 📊 `amazon_prime_titles.csv`: Raw Prime Video titles dataset
* 📈 `amazon.info.pbix`: Power BI file with full interactive dashboard
* 📝 `README.md`: Project overview, KPIs, and key insights
