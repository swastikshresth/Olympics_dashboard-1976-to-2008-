# **Olympics Dashboard Analysis (1976–2008)**

## **ETL Process (As per your method)**

### **Step 1: Extract**

* CSV data file imported **directly into Power BI**.
* No use of SQL; data loaded via **Power Query Editor**.

---

### **Step 2: Transform (Data Cleaning in Power Query Editor)**

#### **Key Cleaning Steps You Likely Performed:**

1. **Removed Duplicates:**

   * Ensured no duplicate athlete records or medal counts.

2. **Checked Nulls/Missing Values:**

   * Replaced missing gender or medal fields with appropriate defaults or removed irrelevant rows.

3. **Standardized Text Data:**

   * Trimmed extra spaces (e.g., Country names, Athlete names).

4. **Filtered Date Range:**

   * Limited data from **1976 to 2008** using slicers.

5. **Correct Data Types:**

   * Year → Whole Number
   * Medal → Text
   * Athlete Name → Text
   * Medal Count → Numeric

6. **Created Measures:**

   * DAX measures for **Total Medal Count, Gold, Silver, Bronze counts**.

---

### **Step 3: Load**

* Final clean data loaded into Power BI model.
* Visuals and KPIs created from the model.

---

## **Key Insights from Your Dashboard**

### **1. Overall Medal Counts (1976–2008)**

* **Total Medals:** 15.32K
* **Gold:** 5.04K
* **Silver:** 5.02K
* **Bronze:** 5.26K

**Insight:**
Bronze medals are the highest in count, indicating tough competition where more athletes end up in 3rd place.

---

### **2. Gender Participation**

* **Men:** 9.39K medals
* **Women:** 5.93K medals

**Insight:**
Men dominate medal wins, but there’s significant women’s participation, reflecting historical trends in Olympic gender representation.

---

### **3. Top 5 Countries Performance**

| Country           | Medals |
| ----------------- | ------ |
| **United States** | 928    |
| **Soviet Union**  | 583    |
| **Australia**     | 439    |
| **Germany**       | 316    |
| **China**         | 252    |

**Insight:**
USA leads by a huge margin. Emerging performance of China indicates growth in later years.

---

### **4. Top 5 Sports Categories**

| Sport          | Medals |
| -------------- | ------ |
| **Aquatics**   | 2.2K   |
| **Athletics**  | 1.5K   |
| **Rowing**     | 1.4K   |
| **Hockey**     | 0.8K   |
| **Gymnastics** | 0.8K   |

**Insight:**
Aquatics is the top medal contributor, likely due to multiple swimming events. Athletics and rowing are also high performers.

---

### **5. Athlete-Wise Performance**

Athletes like **ANDRIANOV, Nikolay** and **PHELPS, Michael** have multi-medal achievements, indicating dominance in their categories.

---

## **Recommendations**

### **1. Gender Diversity Programs**

* **Promote Women’s Participation:**
  Encourage programs that continue to support and grow women’s participation in the Olympics.

---

### **2. Focus on High-Impact Sports**

* **Aquatics and Athletics are the largest medal contributors.**
  Countries aiming to improve rankings should focus more on these sports.

---

### **3. Analyze Country Trends**

* Understand why the USA and Soviet Union dominate historically.
* Countries with lower medal counts should **analyze training investments** in underperforming sports.

---

### **4. Recognize Star Athletes**

* Athletes with multiple medals can be studied for training patterns, coaching methods, and support systems.
* Use these case studies to build future training programs.

---

### **5. Build Sports-Specific Strategies**

* For **Rowing, Gymnastics, Hockey**, specific medal strategies can be developed based on historical data and resource allocation.

---

### **6. Periodic Analysis (Future Scope)**

* Extend the dashboard for **post-2008 analysis** to capture recent trends.
* Add **Olympic Year-Wise visualizations** for detailed trend analysis over time.

---

