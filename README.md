# **🚀 KultureHire Data Analyst Internship 🚀**  


# **👋 Introduction :**


As a **Data Analyst Intern at KultureHire**, I have been actively involved in **collecting, cleaning, and analyzing data** to generate actionable insights that support business decision-making. My role encompasses a broad range of analytical tasks, including **developing interactive dashboards, identifying key business trends, and optimizing data strategies** to enhance operational efficiency.  

Utilizing tools such as **SQL, Python, Power BI, and Excel**, I work on **data visualization, reporting, and creating well-structured documentation** to ensure stakeholders have access to accurate and meaningful insights. Additionally, I am responsible for **making reports, documenting analytical processes, and preparing presentations** to effectively communicate data-driven findings to both technical and non-technical audiences.  

This internship has provided me with hands-on experience in working with real-world datasets, strengthening my analytical and problem-solving skills, and enhancing my ability to present insights through **clear and compelling reports, documentation, and presentations**.  

# **🎯 Objective :**

The primary goal of this project was to analyze and interpret career-related preferences and behavioral patterns of Gen-Z individuals using real survey data. The project seeks to bridge the gap between what Gen-Z wants and what the current job market is offering.

Specific objectives included:

- To identify **top career aspirations** and preferred industries among Gen-Z candidates.
  
- To analyze the **work environment preferences** — such as remote, hybrid, or on-site work — and the reasons behind those preferences.
- To explore **salary expectations** and how they vary across education levels, gender, and geographical regions.
- To understand the importance of **work-life balance, mental health, job security**, and **flexibility** in Gen-Z's career decisions.
- To examine the **influence of social media, peer trends**, and **brand perception** on career choices.
- To present the findings through interactive **dashboards** and **clear visualizations**, offering actionable insights for organizations and stakeholders.

This data-driven study contributes to the broader effort of aligning talent acquisition strategies with the values and expectations of the emerging workforce.



# **🛠️ Tools Used :**

To carry out this project efficiently and present results in a meaningful way, I utilized a variety of tools from the modern data analytics stack:

## 📌 **Excel :**
Microsoft Excel was used for initial data preprocessing and quick checks. It was also used to validate key statistical summaries and create pivot tables for exploratory review.

## 📌 **Python :**
Used for data cleaning, manipulation, and exploratory data analysis (EDA). Libraries such as `Pandas`, `NumPy`, `Matplotlib`, and `Seaborn` were employed to uncover patterns and prepare data for visualization.

## 📌 **Power BI :**
Power BI was used to create **interactive dashboards** that made the insights easily digestible for stakeholders. The tool allowed for dynamic filtering, storytelling, and visual summaries of complex datasets.


## 📌 **MySQL:**
If SQL was used in your project: SQL queries were used to extract meaningful segments of data, group and filter responses based on categorical variables, and structure the data for analysis and visualization.

------

# **👋 Key Contributions :**  

During my **Data Analyst Internship at KultureHire**, I have contributed to various aspects of the data analysis process, from data collection to visualization and presentation. My key contributions include:  

#### **1. Problem Statement Definition**  
- Identified the core business problem to be addressed through data analysis.  
- Defined key objectives and formulated a structured approach to solving the problem using data-driven insights.  

#### **2. Data Collection for Project**  
- Designed and deployed a **Google Form** to collect relevant data for analysis.  
- Ensured data integrity by structuring the form to capture accurate and complete responses.  

#### **3. Data Cleaning and Standardization (Excel)**  
- Cleaned raw data by handling missing values, duplicates, and inconsistencies.  
- Standardized data formats to ensure consistency and accuracy in further analysis.  

#### **4. Exploratory Data Analysis (Excel)**  
- Conducted **descriptive statistics and trend analysis** to uncover patterns and anomalies in the dataset.  
- Used pivot tables, charts, and conditional formatting to gain preliminary insights.  

#### **5. Data Analysis in MySQL**  
- Wrote and executed **SQL queries** to extract, filter, and aggregate data for deeper analysis.  
- Performed **joins, subqueries, and window functions** to analyze relationships between different data points.  

#### **6. Executive Dashboard in Excel**  
- Built an **interactive executive dashboard** in Excel to present key metrics and insights.  
- Used advanced Excel features like **Power Query, slicers, and dynamic charts** to enhance data visualization.  

#### **7. Functional Dashboard in Power BI**  
- Developed a **functional Power BI dashboard** with interactive visuals to provide deeper insights.  
- Implemented **DAX measures and KPIs** to enhance reporting and analytical capabilities.  

#### **8. Project Report**  
- Documented the entire project lifecycle, including **problem definition, methodology, analysis, and findings**.  
- Created a well-structured report that provides a **comprehensive overview** of the analysis and recommendations.  

#### **9. Project Presentation**  
- Designed and delivered a **professional presentation** summarizing key findings and insights.  
- Effectively communicated complex data analysis results to both technical and non-technical stakeholders.  

This internship has enhanced my skills in **data collection, analysis, visualization, and reporting**, equipping me with hands-on experience in executing end-to-end data projects.  


---

# **🔄 Project Workflow (Detailed Version) :**

This project was structured around a clearly defined workflow that moved through each phase of the data analytics lifecycle. From identifying the problem to communicating final results, every step was carefully designed to ensure high-quality analysis and actionable insights for stakeholders. Here's an in-depth breakdown of each stage:



## 🧩 **1. Problem Statement Documentation :**

The project began by identifying and defining the core problem the analysis aimed to solve:  
> **“What are the career expectations, job preferences, and motivations of Gen-Z individuals entering the workforce?”**

Given the evolving nature of work and the unique values of Generation Z, this project set out to uncover insights that could assist hiring managers, recruiters, and organizational leaders in better aligning their workplace culture and recruitment strategies with Gen-Z priorities.

To ensure clarity and alignment, a brief was prepared in collaboration with mentors at **KultureHire**. This document laid out the **key business questions**, such as:
- What industries or job roles does Gen-Z find most appealing?
- What work formats (remote, hybrid, on-site) do they prefer, and why?
- How do salary expectations vary by gender, education level, and region?
- What non-monetary values influence their job decisions (flexibility, mental health support, purpose, etc.)?



## 📥 **2. Data Collection :**

To gather relevant data, I designed a comprehensive survey using **Google Forms** that targeted Gen-Z respondents from diverse academic and geographical backgrounds. The form included both multiple-choice and open-ended questions to capture:
- Preferred career fields and job roles  
- Work style preferences (remote vs. on-site)  
- Expected salary range  
- Motivating workplace values (e.g., work-life balance, mental health, social impact)  
- Demographic data (age, gender, education, location)

The form was distributed through educational networks, social media platforms, and peer sharing.

🔗 **Google Form Link :** - [https://docs.google.com/forms/d/e/1FAIpQLSdNX5VW8Bu-noqdxQOD_WxTIK_YO6sr8WvShI8nXMS0XXx7tg/viewform?usp=dialog] 

This ensured a broad and representative dataset of Gen-Z opinions and expectations.


## 🧹 **3. Data Cleaning & Standardization (Excel):**

Before analyzing the Career_Aspirations dataset, it’s essential to clean and prepare the data to ensure accuracy and consistency. This involves using Excel tools like Text to Columns, Find & Replace, IF formulas, and data type formatting to standardize the dataset and remove inconsistencies. A clean dataset ensures reliable insights and effective SQL querying.


#### ✅ 1. **Text to Columns**
- Use **Text to Columns** to separate values if they’re combined (e.g., Date and Time in the same cell).

- Go to:  
  **Data → Text to Columns → Delimited (e.g., comma, tab) → Finish**
- Example: Split combined columns like `Date/Time` into separate `Date` and `Time` fields.

---

#### ✅ 2. **Find & Replace**

- Used to clean inconsistent entries, fix typos, or remove unwanted characters (like extra spaces or special characters).


- Go to:  
  **Home → Find & Select → Replace**
- Example:
  - Replace `self-sponser` with `self-sponsor`
  - Replace `Closet Carrer to Aspirational Job` with `Closest Career to Aspirational Job`

---

#### ✅ 3. **IF Statements**
- Use `IF()` formulas to create logical flags or fix inconsistent data.
- Example:
  ```excel
  =IF(A2="Not Mentioned", "Unknown", A2)
  ```
  - Replace "Not Mentioned" values with "Unknown" or blanks.
  - Identify low salaries:
    ```excel
    =IF(B2<20000, "Low", "Acceptable")
    ```

---

#### ✅ 4. **Changing Data Types**
- Ensure correct formats:
  - **Date Columns** → Format as `Date`
  - **Salary Columns** → Remove symbols like `k`, `>`, and convert ranges like `31k to 40k` to numeric midpoints (e.g., `35,000`)
    - Use helper columns and formulas:
      ```excel
      =MID(A2,1,FIND("k",A2)-1)*1000
      ```
      or manually input average values.
  - **Yes/Maybe/No** columns → Convert to standardized ENUM-like formats if needed.

---

#### ✅ 5. **Trimming Extra Spaces**
- Use `TRIM()` to clean up entries:
  ```excel
  =TRIM(A2)
  ```

---

#### ✅ 6. **Standardizing Values**
- Ensure consistent casing (e.g., "Hybrid" vs "hybrid")
- Use `PROPER()` to make values consistently capitalized:
  ```excel
  =PROPER(A2)
  ```

---

#### ✅ 7. **Remove Duplicates**
- Use **Data → Remove Duplicates** to ensure unique responses, especially if email IDs are present.



## 🔍 **4. Exploratory Data Analysis (EDA) using Excel:**

With the cleaned dataset in place, I used Excel to perform exploratory analysis. The goal was to understand the distribution and structure of the data before deeper analysis.


Use SQL querying to answer given business questions. Provide queries to business questions and deliver insights.

**1. What industries are Gen-Z most interested in pursuing careers in?**

**2. What are the top factors influencing Gen-Z’s career choices?**

**3. What is the desired work environment for Gen-Z? (e.g., remote, hybrid, in-office)**

**4. How do financial goals, such as salary and benefits, impact career aspirations among Gen-Z?**

**5. What role do personal values and social impact play in career choices for Gen-Z?**



## 🧮 **5. Data Analysis using SQL :**

This analysis explores Gen-Z’s career aspirations using survey data collected through the Career_Aspirations table. By leveraging SQL queries, we aim to uncover key insights about the industries Gen-Z is drawn to, the factors influencing their choices, and their preferences around work environments, financial goals, and personal values.


### ✅ **1. What industries are Gen-Z most interested in pursuing careers in?**

```sql
SELECT Closest_Career_to_Aspirational_Job, COUNT(*) AS Count  
FROM Career_Aspirations  
GROUP BY Closest_Career_to_Aspirational_Job  
ORDER BY Count DESC;
```


---

### ✅ **2. What are the top factors influencing Gen-Z’s career choices?**

```sql
SELECT Top_Factors_Influencing_Career_Aspirations, COUNT(*) AS Count 
FROM Career_Aspirations  
GROUP BY Top_Factors_Influencing_Career_Aspirations  
ORDER BY Count DESC;
```

---

### ✅ **3. What is the desired work environment for Gen-Z? (e.g., remote, hybrid, in-office)**

```sql
SELECT Most_Preferred_Work_Environment, COUNT(*) AS Count   
FROM Career_Aspirations  
GROUP BY Most_Preferred_Work_Environment  
ORDER BY Count DESC;
```

---

### ✅ **4. How do financial goals, such as salary and benefits, impact career aspirations among Gen-Z?**

```sql
SELECT Minimum_In_Hand_Salary_First_3_Years, Expected_In_Hand_Salary_After_5_Years, COUNT(*) AS Count  
FROM Career_Aspirations  
GROUP BY Minimum_In_Hand_Salary_First_3_Years, Expected_In_Hand_Salary_After_5_Years  
ORDER BY Count DESC;
```


---

### ✅ **5. What role do personal values and social impact play in career choices for Gen-Z?**

```sql
SELECT Likelihood_of_Working_for_a_Non_Social_Impact_Company, COUNT(*) AS Count 
FROM Career_Aspirations 
GROUP BY Likelihood_of_Working_for_a_Non_Social_Impact_Company 
ORDER BY Count DESC;
```

---


# 📊 **6. Executive Dashboard in Excel :**

An executive summary dashboard was developed in Excel, aimed at non-technical stakeholders. It featured:
- Key metrics and KPIs (e.g., top career sectors, average salary expectations)
- Simplified visuals for quick review
- Charts showing relationships between variables (e.g., gender vs. work preference)
- Insights organized into clearly labeled sections


## **Excel Dashboard :**



---

### 📈 7. Functional Dashboard in Power BI

To bring the data to life, I created an **interactive dashboard** in **Power BI**, offering dynamic filtering, cross-drill analysis, and customized visualizations.

Key features:
- Filter by age group, gender, or education level
- View heatmaps and stacked bar charts for industry preferences
- Analyze geographic trends and remote work preferences across regions
- A "What Gen-Z Wants" summary card that highlights key motivators

Power BI’s powerful visual and interactive capabilities made it easier for decision-makers to explore insights hands-on.

---

### 🗣️ 8. Project Presentation

To wrap up the project, I developed a presentation that summarized the entire process, findings, and recommendations. It included:
- An overview of the methodology and tools used  
- Key insights supported by visuals  
- Screenshots of dashboards  
- Actionable recommendations for talent acquisition and employee engagement strategies  

The project was shared with my mentors at **KultureHire** and peers for feedback and discussion, reinforcing the value of data-driven storytelling.

---

Would you like me to help design a **project diagram or Gantt-style timeline**, or structure this as a full `README.md` for your GitHub repo?
