# Tech Jobs Survey Analysis

---

### Table of Contents

- [Overview](#overview)
- [Problem Statement](#problem-statement)
- [Data](#data)
- [Approach](#approach)
- [Tools And Technologies](#tools-and-technologies)
- [Project Files](#project-files)
- [Project Outcome](#project-outcome)
- [How To Run](#how-to-run)
- [Conclusion](#conclusion)
- [License](#license)
- [Author Info](#author-info)

[Back to the Top](#tech-jobs-survey-analysis)

---

## Overview  

This project analyzes current and future technology skill trends using job postings and survey data. It combines **API data extraction**, **web scraping**, and **visualization** to identify which programming languages and technologies are in high demand across different locations. The analysis helps stakeholders in tech hiring and career planning by highlighting which tools and skills dominate the job market.

[Back to the Top](#tech-jobs-survey-analysis)

---

## Problem Statement  

The technology job market evolves rapidly, making it difficult for professionals and recruiters to keep up with in-demand skills. This project aims to provide actionable insights into the most requested programming languages and technologies, broken down by location and salary, using real-time job data and survey results.

[Back to the Top](#tech-jobs-survey-analysis)

---

## Data  

- **API Source**: IBM Skills Network job dataset (JSON format)  
- **Scraped Data Source**: Salary table from public HTML page  
- **Survey Data**: `m5_survey_data_technologies_normalised.csv`, `m5_survey_data_demographics.csv`  
- **Description**:
  - Job postings include location, title, key skills
  - Salary data includes language and average pay
  - Survey data includes tech usage (current/future) and demographics
  - Total records analyzed: 8,000+ (combined across all sources)

[Back to the Top](#tech-jobs-survey-analysis)

---

## Approach  

1. **Data Exploration & Cleaning**
   - Loaded and normalized CSV survey data using `pandas`
   - Extracted job and skill data from JSON API
   - Cleaned HTML salary table using `BeautifulSoup`

2. **Feature Engineering**
   - Extracted programming languages from “Key Skills” column
   - Created summary tables for most popular technologies and job locations
   - Mapped salaries to programming languages

3. **Visualization**
   - Bar charts for:
     - Job postings by programming language
     - Job postings by location
     - Average annual salary by language (color-coded by salary range)
   - Power BI dashboards for survey insights (current vs future tech use, demographics)

4. **Analysis**
   - Counted total job postings per tech skill
   - Identified top job markets (e.g., New York, San Francisco)
   - Compared salary trends across languages like Python, C++, SQL, and JavaScript

[Back to the Top](#tech-jobs-survey-analysis)

---

## Tools and Technologies  

- Python (pandas, matplotlib, BeautifulSoup, requests)  
- Jupyter Notebook  
- Microsoft Power BI  
- PowerPoint (for stakeholder presentation)  
- Git & GitHub  

[Back to the Top](#tech-jobs-survey-analysis)

---

## Project Files

The following are the files in this project:

- [Survey Data](data/m5_survey_data_technologies_normalised.csv)
- [Survey Demographics Data](data/m5_survey_data_demographics.csv)
- [Microsoft Power BI Report](TechJobsSurveyReport.pbix)
- [Microsoft Powerpoint Presentation](TechJobsSurveyPresentation.pptx)
- [Jupyter Notebook for Survey Analysis](TechJobsSurveyAnalysis.ipynb)
- [Jupyter Notebook for Salary Analysis](TechJobsSalaryAnalysis.ipynb)

[Back to the Top](#tech-jobs-survey-analysis)

---

## Project Outcome  

- **Most In-Demand Skills**: Python, SQL, and Typescript were among the top requested technologies across job listings  
- **Top Job Locations**: Washington DC and Detroit led in tech job volume  
- **Salary Insights**: Languages like Swift and Python fetched higher average annual salaries (> $120,000), while PHP and HTML trailed  
- **Visualization Impact**: Power BI dashboard enabled fast interpretation of survey and tech skill adoption data for strategic hiring decisions


[Back to the Top](#tech-jobs-survey-analysis)

---

## How to Run  
1. Clone the repository:
   ```bash
   git clone https://github.com/prasanna-sriram/tech-jobs-survey-analysis.git

2. Open the Jupyter Notebooks:

    - Tech-Survey-Data-Analysis.ipynb
    - Tech-Survey-Salary-Analysis.ipynb

3. Run the cells to reproduce API analysis, visualizations, and scraping results.

4. Open FinalProjectReport.pbix for Power BI dashboard.

[Back to the Top](#tech-jobs-survey-analysis)

---

## Conclusion  

This end-to-end analysis offers a snapshot of today’s tech job landscape by merging multiple data sources — API, survey, and web scraping — into actionable visuals. It provides insights for recruiters, job seekers, and curriculum designers aiming to stay aligned with industry demand. Future extensions could include tracking job trends over time and building an automated job trend tracker.

[Back to the Top](#tech-jobs-survey-analysis)

---

## License

MIT License

Copyright (c) [2025] [Prasanna Sriram]

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.

[Back to the Top](#tech-jobs-survey-analysis)

---

## Author Info

- Github - [Github Profile](https://github.com/prasanna-sriram)
- LinkedIn - [Prasanna Sriram](https://www.linkedin.com/in/prasanna-sriram/)
- Tableau - [Tableau Public Profile](https://public.tableau.com/app/profile/prasanna.sriram.ps)

[Back to the Top](#tech-jobs-survey-analysis)