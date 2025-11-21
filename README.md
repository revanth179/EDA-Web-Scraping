**Web Scraping and Exploratory Data Analysis on Samsung Mobile Phones Dataset**

**Project Overview**

In today's competitive smartphone market, customers struggle to compare devices due to varying features and price differences. This project aims to solve that by extracting structured data from Flipkart and analyzing how key features affect smartphone pricing — specifically for Samsung mobile phones.

**Goal:**
Understand how specifications such as RAM, ROM, Battery, Camera, and Processor impact the pricing of Samsung smartphones.

**Objectives**

**✔️ Web Scraping**

Scraped Samsung smartphone data from Flipkart using Python, Requests, and BeautifulSoup.

Extracted key specifications:

Price

RAM

ROM

Battery

Processor

Camera

Cleaned text using Regex & loops.

Stored data in a structured Pandas DataFrame for EDA.

**✔️ Data Preprocessing**

Steps included:

Removing unwanted characters

Standardizing column names

Extracting numeric values

Handling missing values

Converting data types

Removing invalid entries

✔️ Exploratory Data Analysis

Performed using Pandas, Matplotlib, & Seaborn.

**📊 Data Visualizations**
**1. Univariate Analysis**

Histograms: Distribution of price, RAM, ROM, battery, camera

Box Plots: Identified outliers & value spread

Count Plots: Frequency of each Samsung model

Pie Chart: Top 5 most frequently-listed models

**2. Bivariate Analysis**

Correlation Heatmap: Identified feature relationships

Bar Chart: Avg price vs RAM capacity

Scatter Plot: Battery vs price (low correlation)

Violin Plot: Price distribution by RAM variants

Business Questions Addressed

Which Samsung models are most popular on Flipkart?

How do RAM, ROM, battery, and camera affect mobile pricing?

Which specification has the strongest pricing influence?

What price ranges do most Samsung phones fall into?

Do higher specs show predictable price patterns?

**Conclusion**

RAM, processor, and camera quality strongly influence smartphone pricing.

Battery capacity has moderate impact.

Most Samsung models fall in the mid-range price segment.

Samsung focuses heavily on mid-budget and mid-premium markets.

Project improved our hands-on skills in:

Web scraping

Data cleaning

EDA

Extracting real-world insights from unstructured data

**Challenges Faced**

Dynamic website content / anti-scraping restrictions

Cleaning inconsistent spec formats (GB, mAh, MP, GHz)

Extracting numeric values from mixed text

Handling missing values, duplicates, and outliers

Ensuring accurate and reliable scraped data

**Project Files**

📘 Mobile_EDA_Project.ipynb (Notebook)

📊 Flipkart.pptx (Project Presentation)

📄 README.md

📁 Dataset (Scraped & cleaned)

**🔧 Tech Stack**

Python

Requests

BeautifulSoup

Pandas

NumPy

Matplotlib

Seaborn

Regex

**🔗 Connect With Us**

Revanth’s LinkedIn: www.linkedin.com/in/revanthsaikumarmanyam

GitHub: https://github.com/revanth179
