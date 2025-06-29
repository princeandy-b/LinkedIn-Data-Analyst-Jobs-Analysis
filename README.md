
# Data Analyst Job Postings on LinkedIn: Comparative Analysis (Africa, Canada, USA)

## Overview

This project analyzes Data Analyst job postings from LinkedIn across three regions: **Africa**, **Canada**, and the **USA**. The dataset, sourced from Kaggle, provides insights into the current job market for Data Analysts, including experience requirements, in-demand skills, popular job titles, and the prevalence of remote, onsite, and hybrid roles.

## Dataset

- **Source:** [Kaggle - Data Analyst Job Postings on LinkedIn](https://www.kaggle.com/datasets/cedricaubin/linkedin-data-analyst-jobs-listings)
- **Regions Covered:** Africa, Canada, USA
- **Features:** Job title, required skills, years of experience, job type (onsite/remote/hybrid), and more.

## Key Insights

### 1. Experience Requirements

- **Africa:** Most roles require 2-5 years of experience, with a few outliers demanding up to 20 years.
- **Canada:** Similar trend, but a slightly higher proportion of roles require 3-5 years.
- **USA:** Majority of postings require 2-4 years, with rare postings asking for 20 years.

![Experience Requirement Distribution Africa](images/Experience%20Requirement%20Distribution%20%28Africa%29.png)
![Experience Requirement Distribution Canada](images/Experience%20Requirement%20Distribution%20%28Canada%29.png)
![Experience Requirement Distribution USA](images/Experience%20Requirement%20Distribution%20%28USA%29.png)


---

### 2. Most In-Demand Skills

- **Common Skills:** SQL, R, Python, and Excel are consistently in high demand across all regions.
- **Regional Variations:**  
  - Africa: R and SQL are most sought after.  
  - Canada: R, SQL, and Python lead.  
  - USA: R and SQL dominate, with Python and Excel also prominent.

![Most in-demand skills Africa](./images/Most%20in-demand%20skills%20%28Africa%29.png)
![Most in-demand skills Canada](./images/Most%20in-demand%20skills%20%28Canada%29.png)
![Most in-demand skills USA](./images/Most%20in-demand%20skills%20%28USA%29.png)

---

### 3. Top Job Titles

- "Data Analyst" is the most common title in all regions.
- Other frequent titles include "Junior Data Analyst", "Senior Data Analyst", and specialized analyst roles.


![Top Data Analyst Job titles Africa](./images/Top%20Data%20Analyst%20Job%titles%20%28Africa%29.png)
![Top Data Analyst Job titles Canada](./images/Top%20data%20analyst%20job%titles%20%28Canada%29.png)
![Top Data Analyst Job titles USA](./images/Top%20data%20analyst%20job%titles%20%28USA%29.png)

---

### 4. Remote vs Onsite vs Hybrid Roles

- All three regions show a relatively balanced distribution among onsite, remote, and hybrid roles, with a slight preference for onsite in Canada.

![Work Schedule Chart Africa](./images/Work%20Schedule%20chart%20%28Africa%29.png)
![Work Schedule Chart Canada](./images/Work%20Schedule%20Chart%20%28Canada%29.png)
![Work Schedule Chart USA](./images/Work%20schedule%20chart%20%28Africa%29.png)

---

## How to Use

1. **Clone the Repository**
   ```bash
   git clone https://github.com/yourusername/data-analyst-job-postings.git
   cd data-analyst-job-postings
   ```

2. **Explore the Notebooks**
   - Jupyter notebooks for data cleaning, analysis, and visualization are provided in the `notebooks/` directory.

3. **View the Visualizations**
   - All key insights and plots are available in the `images/` directory.

## Requirements

- Python 3.8+
- pandas
- matplotlib
- seaborn
- jupyter (optional, for running notebooks)




## License

This project is for educational and research purposes. Please refer to the original [Kaggle dataset license](https://www.kaggle.com/) for data usage terms.

---
