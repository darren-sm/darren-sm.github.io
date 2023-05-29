# Portfolio Website
![web demo](assets/demo.gif)

See it live at: [https://darren-sm.github.io/](https://darren-sm.github.io/)
Contains a quick summary about me. The portolio lists out the significant projects I did. This website is made with bootstrap framework
## Projects
Below are some projects I made:
### 1. Weather ELT Pipeline
<img src="https://raw.githubusercontent.com/darren-sm/darren-sm.github.io/main/assets/1.png?token=GHSAT0AAAAAACA2BAC6OXVC3QA7IKJMM6AUZDULCJA" alt="Image asset/1.png" style="zoom:50%;" />

**Source Code**: [GitHub Link](https://github.com/darren-sm/Weather-Data-Pipeline)

Data Pipeline for [NOAA Global Surface Summary of the Day (GSOD)](https://www.ncei.noaa.gov/access/metadata/landing-page/bin/iso?id=gov.noaa.ncdc:C00516), utilizing Apache Airflow for weather data orchestration and Docker for containerization. The program collects 1999-present weather data from over 10,000 stations worldwide, totaling over 1.4 billion records or 12 GB of data. Also, I've designed an interactive dashboard with Metabase  providing real-time visualizations and analytics

### 2. r/all PH web scraping and data analysis
<img src="https://raw.githubusercontent.com/darren-sm/Reddit-PH-Frontpage/main/docs/wordcloud.png" alt="r/Art" style="zoom:50%;" />

**Source Code**: [GitHub Link](https://github.com/darren-sm/Reddit-PH-Frontpage)

Gather and analyze 1000 popular posts from the Reddit's front page for Philippine users using web scraping techniques, including proxy rotation to avoid triggering rate limit violations.

- Optimized data retrieval by leveraging Reddit's API and implementing multi-threading for parallel execution of requests.
- Developed an insightful data visualization using Jupyter Notebook and the matplotlib library.

### 3. Crypto Data Pipeline
**Source Code**: [GitHub Link](https://github.com/darren-sm/crypto-data-pipeline)

Data pipeline for top 100 cryptocurrency coins data using [Coingecko API](https://www.coingecko.com/en/api/documentation). The data pipeline is made as a function in [Google Cloud Function](https://cloud.google.com/functions) to be executed every 5 minutes through [Google Cloud Scheduler](https://cloud.google.com/scheduler) trigger
