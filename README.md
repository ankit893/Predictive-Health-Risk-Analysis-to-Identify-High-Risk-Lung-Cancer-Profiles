🫁 Lung Cancer Survey Analysis Using Python

📌 Project Overview

This project explores a Lung Cancer Survey dataset using Python to identify patterns, trends, and potential risk factors associated with lung cancer among male and female respondents.

The analysis focuses on demographic characteristics, behavioral factors, symptoms, and health conditions that may contribute to lung cancer prevalence.
Using Python's data analysis and visualization libraries, this project provides insights into age distribution, smoking behavior, symptom occurrence, and relationships between various health indicators.

🎯 Business Problem

Early detection of lung cancer remains a significant challenge in healthcare. Understanding behavioral, demographic, and symptom-related patterns can help healthcare professionals identify high-risk individuals and support preventive healthcare strategies.



🔎 Problem Statement

The objective of this analysis is to:

* Identify demographic groups with higher lung cancer prevalence.
* Examine relationships between smoking habits and lung cancer.
* Analyze common symptoms associated with lung cancer cases.
* Explore correlations among health-related attributes.
* Provide data-driven insights that support awareness and early intervention efforts.



📊 Dataset Information

Source

Public Lung Cancer Survey Dataset

Records

309 Survey Responses

Features

16 Variables including demographic information, behavioral factors, symptoms, and lung cancer status.

| Column Name           | Description                        |
| --------------------- | ---------------------------------- |
| GENDER                | Gender of respondent (Male/Female) |
| AGE                   | Age of respondent                  |
| SMOKING               | Smoking habit indicator            |
| YELLOW_FINGERS        | Presence of yellow fingers         |
| ANXIETY               | Anxiety condition                  |
| PEER_PRESSURE         | Peer influence indicator           |
| CHRONIC DISEASE       | Presence of chronic disease        |
| FATIGUE               | Fatigue condition                  |
| ALLERGY               | Allergy condition                  |
| WHEEZING              | Wheezing symptom                   |
| ALCOHOL CONSUMING     | Alcohol consumption habit          |
| COUGHING              | Presence of cough                  |
| SHORTNESS OF BREATH   | Breathing difficulty               |
| SWALLOWING DIFFICULTY | Difficulty swallowing              |
| CHEST PAIN            | Presence of chest pain             |
| LUNG_CANCER           | Target variable (YES/NO)           |



🛠️ Tools & Technologies Used

Programming Language

✔ Python

Libraries

✔ Pandas – Data manipulation and analysis

✔ NumPy – Numerical computations

✔ Matplotlib – Data visualization

✔ Seaborn – Statistical visualizations

⚡ Data Analysis Workflow

1️⃣ Data Loading and Exploration

* Imported dataset using Pandas.
* Inspected dataset structure using:

  * `head()`
  * `tail()`
  * `info()`
  * `shape`
  * `describe()`

2️⃣ Data Quality Assessment

* Verified dataset dimensions.
* Checked data types.
* Confirmed absence of missing values.
* Reviewed feature distributions.

3️⃣ Exploratory Data Analysis (EDA)

Performed statistical and visual analysis to uncover trends and relationships.

Visualizations Created

📈 Age Distribution Analysis

* Distribution of respondents by age.
* Identification of dominant age groups.

🚬 Smoking vs Lung Cancer Analysis

* Comparison between smoking behavior and lung cancer status.

👨‍⚕️ Gender Distribution Analysis

* Lung cancer prevalence among male and female respondents.

🤒 Symptom-Based Analysis

Investigation of:

* Coughing
* Wheezing
* Chest Pain
* Shortness of Breath

📊 Correlation Analysis

* Generated correlation matrix.
* Visualized relationships using a heatmap.

📦 Box Plot Analysis

* Age distribution by lung cancer status.
* Age distribution by gender and lung cancer status.

🔍 Pair Plot Analysis

* Multi-variable relationship exploration.
* Pattern detection across numerical features.



📊 Key Visualizations

Correlation Heatmap

Identifies relationships among symptoms, habits, and health conditions.

Age vs Lung Cancer Box Plot

Highlights age differences between respondents with and without lung cancer.

Gender and Age Distribution

Compares lung cancer occurrence across gender groups and age ranges.

Symptom Distribution Analysis

Shows the prevalence of symptoms among respondents diagnosed with lung cancer.


📈 Key Insights

✅ Age Group Findings

The majority of respondents diagnosed with lung cancer were concentrated within:

* Female respondents aged 50–59 years
* Female respondents aged 60–69 years
* Male respondents aged 50–59 years
* Male respondents aged 60–69 years

✅ Symptom Trends

Common symptoms frequently observed among lung cancer respondents included:

* Coughing
* Wheezing
* Chest Pain
* Shortness of Breath

✅ Behavioral Factors

Smoking-related indicators such as smoking behavior and yellow fingers showed noticeable associations with lung cancer cases.

✅ Correlation Findings

Several symptom-related variables demonstrated moderate positive correlations, indicating potential relationships among respiratory health indicators.



📁 Project Structure


🚀 How to Run the Project

Clone the Repository




Install Required Libraries

```bash
pip install pandas numpy matplotlib seaborn

Run Jupyter Notebook

```bash
jupyter notebook


Open:
Lung_Cancer_Analysis.ipynb
and execute all cells.

🔮 Future Improvements

* Build predictive machine learning models.
* Perform feature importance analysis.
* Develop an interactive dashboard using Streamlit.
* Compare classification algorithms for lung cancer prediction.
* Implement model evaluation metrics and cross-validation.

🏆 Project Outcomes

This project demonstrates practical skills in:

* Exploratory Data Analysis (EDA)
* Data Cleaning and Validation
* Statistical Analysis
* Data Visualization
* Healthcare Data Analytics
* Python Programming

📌 About Me

Hi, I'm Ankit Sharma, a Data Analyst skilled in SQL, Python, Power BI, and Excel.

I enjoy transforming raw data into meaningful insights through analytics, visualization, and storytelling.

🔹 Skills

* SQL
* Python
* Power BI
* Excel
* Data Cleaning
* Data Visualization
* Business Intelligence

🔹 Interests

* Data Analytics
* Dashboard Development
* Machine Learning
* Data Storytelling

📫 Email: [ankitsharmaaa893@gmail.com]
🔗 LinkedIn: https://www.linkedin.com/in/ankitsharma893/
⭐ If you found this project helpful, please consider starring the repository.
