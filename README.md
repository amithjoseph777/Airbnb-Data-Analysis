# 🏡 Airbnb Data Analysis: Enhancing Host Strategies

![Airbnb Logo](https://upload.wikimedia.org/wikipedia/commons/6/69/Airbnb_Logo_Bélo.svg)

## 📌 Project Overview
This project analyzes **Airbnb hosting strategies** using data analytics to optimize pricing, maximize occupancy rates, and improve guest experiences.  

### **Key Focus Areas:**
- Understanding **how amenities impact pricing and guest ratings**  
- Identifying **seasonal trends and dynamic pricing strategies**  
- Analyzing **neighborhood-wise demand and investment potential**  
- Examining **host behavior and its effect on occupancy rates**  

The insights from this analysis can help **Airbnb hosts and investors** make **data-driven decisions** to improve profitability.

---

## 📊 Dataset Description
This analysis is based on publicly available datasets from **Inside Airbnb** ([Get the Data](https://insideairbnb.com/get-the-data/)), focusing on **San Diego, California**.  

### **Datasets Used:**
📌 **Listings Dataset** – Includes property details, pricing, amenities, and host information.  
📌 **Calendar Dataset** – Provides daily availability, price fluctuations, and seasonal demand trends.  
📌 **Reviews Dataset** – Captures guest feedback, review scores, and sentiment analysis.  

By merging these datasets, **guest preferences, pricing trends, and booking behavior** were analyzed.

---

## 🔄 Data Preprocessing
Before conducting the analysis, data preprocessing was performed with the following steps:

✔️ **Removed unnecessary columns** (URLs, metadata, redundant fields).  
✔️ **Handled missing values** (using averages, replacing nulls with 'Unknown').  
✔️ **Standardized text & date formats** (converted symbols, handled time-based calculations).  
✔️ **Created new features**, including:  
   - Duration of host activity  
   - Number of reviews per month  
   - Adjusted bathroom counts based on privacy (private/shared)  

After preprocessing, the datasets were merged into a **unified dataset** for in-depth analysis.

---

## 📈 Key Findings

### 1️⃣ **Guest Experience Insights**
- **Cleanliness, location, and spaciousness** are the most critical factors influencing guest ratings.
- Listings with **kitchens and free Wi-Fi** tend to receive **higher ratings**.

### 2️⃣ **Pricing & Seasonal Trends**
- **Prices peak in December** due to holiday demand.
- **Mid-week and weekend rates** are consistently higher.

### 3️⃣ **Neighborhood Analysis**
- **Downtown San Diego** has the highest number of bookings.
- **Local hosts** receive better reviews than corporate-run listings.

### 4️⃣ **Host Performance**
- **Superhosts have higher occupancy rates and better ratings** than regular hosts.
- Faster **response time and higher acceptance rates** lead to improved revenue.

---

## 🛠️ Tools & Technologies Used
🔹 **Python** – Data processing and analysis (`pandas`, `numpy`)  
🔹 **Data Visualization** – `matplotlib.pyplot`, `seaborn`, `folium` (interactive maps)  
🔹 **Statistical Analysis** – `scipy` (T-tests, correlations)  
🔹 **Text Processing** – `wordcloud`, `CountVectorizer`  

---

## 🚀 How to Run the Project

### 1️⃣ Clone the Repository
```bash
git clone https://github.com/amithjoseph777/Airbnb-Data-Analysis.git
cd Airbnb-Data-Analysis


