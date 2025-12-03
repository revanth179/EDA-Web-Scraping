# 📱 Samsung Mobile Phones – Web Scraping & Exploratory Data Analysis (EDA)
### *A Real-World Data Analytics Project using Flipkart Dataset*

---

## 📸 Project Preview  
**Correlation Heatmap**

The correlation heatmap shows that RAM, camera, and ROM have the strongest positive relationship with smartphone price.

<img width="827" height="702" alt="image" src="https://github.com/user-attachments/assets/4e1ca56d-4f56-4fb7-bcec-e06876e24210" />

**Pie Chart**

The pie chart displays the top 5 most frequently listed Samsung models on Flipkart.

<img width="778" height="509" alt="image" src="https://github.com/user-attachments/assets/c1effa39-e878-4b54-ac60-c0832f5e0b0d" />


---

## 🚀 Project Overview

Understanding smartphone pricing is challenging due to variations in RAM, ROM, camera quality, and battery capacity.  
This project extracts **real Samsung phone data from Flipkart**, cleans it, and performs **EDA** to understand:

- Which features influence price
- Popular Samsung models
- Pricing trends across budget, mid-range, and premium phones

---

## 🎯 Goal

**Determine how Samsung smartphone specifications impact their pricing.**

---

## 🗂️ Project Structure

📁 Samsung-Mobile-EDA


├── 📘 Mobile_EDA_Project.ipynb


├── 📊 Flipkart.pptx

├── 📄 README.md

└── 📁 dataset/


---

## ✔️ Objectives

### **1️⃣ Web Scraping**
- Scraped real-time data from Flipkart using:
  - **Requests**
  - **BeautifulSoup**
- Extracted:
  - Price  
  - RAM  
  - ROM  
  - Camera  
  - Battery  
  - Processor  
- Cleaned text using **Regex** and string functions  
- Stored structured data in a Pandas DataFrame  

---

### **2️⃣ Data Preprocessing**
- Removed unwanted characters  
- Standardized column names  
- Extracted numeric values (GB, mAh, MP, etc.)  
- Fixed inconsistent formats  
- Converted data types  
- Handled:
  - Missing values  
  - Duplicates  
  - Invalid entries  

---

### **3️⃣ Exploratory Data Analysis (EDA)**

Performed using **Pandas, Matplotlib, Seaborn**.

#### 📊 **Univariate Analysis**
- Histograms → Distribution of price, RAM, ROM, battery, camera  
- Box Plots → Outliers & data spread  
- Count Plot → Most frequently listed models  
- Pie Chart → Top 5 Samsung models  

#### 🔍 **Bivariate Analysis**
- Correlation Heatmap → Feature relationships  
- Bar Chart → Avg price vs RAM  
- Scatter Plot → Battery vs Price  
- Violin Plot → Price ranges by RAM  

---

## 🧠 Key Business Questions Answered

- Which Samsung models are most frequently listed on Flipkart?  
- How do RAM, ROM, camera, and battery affect pricing?  
- Which feature has the **strongest influence** on price?  
- What price ranges dominate the Samsung market?  
- Do higher specs show predictable pricing patterns?  

---

## 🏁 Conclusion

✔ RAM, processor, and camera significantly influence smartphone pricing  
✔ Battery capacity has **low to moderate** impact  
✔ Most Samsung phones fall in **mid-range pricing**  
✔ Samsung targets **budget + mid-premium** customer segments  
✔ EDA revealed clear price–spec relationships  

---

## 🔧 Tech Stack

| Category | Tools |
|---------|-------|
| **Scraping** | Python, Requests, BeautifulSoup |
| **Cleaning** | Pandas, NumPy, Regex |
| **Visualization** | Matplotlib, Seaborn |
| **Documentation** | Markdown, PPT |

---

## 🧩 Challenges Faced

- Dynamic content & anti-scraping restrictions  
- Cleaning inconsistent units (GB, mAh, MP, GHz)  
- Extracting numeric values from mixed text  
- Handling missing values & outliers  
- Ensuring reliable & accurate scraped data  

---

## 🎓 Learnings

- Real-world **web scraping techniques**  
- Data cleaning & transformation  
- Feature extraction from unstructured text  
- Data visualization & insight generation  
- Understanding mobile pricing analytics  

---

## 📎 Project Files

| File | Description |
|------|-------------|
| `Mobile_EDA_Project.ipynb` | Full code for scraping, cleaning, and EDA |
| `Flipkart.pptx` | Project presentation |
| `dataset/` | Scraped & cleaned dataset |
| `README.md` | Documentation |

---

## 🔗 Connect With Me

👨‍💻 **Revanth**  
🌐 LinkedIn: www.linkedin.com/in/revanthsaikumarmanyam  
💻 GitHub: https://github.com/revanth179  

---

