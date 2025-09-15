# Tech Job Market Trends Analysis with Python, Web Scraping, and Power BI

---

### Table of Contents

- [Executive Summary](#executive-summary)
- [Business Problem](#business-problem)
- [Methodology](#methodology)
- [Data](#data)
- [Skills](#skills)
- [Results and Business Recommendation](#results-and-business-recommendation)
- [Project Files](#project-files)
- [How To Run](#how-to-run)
- [Next Steps](#next-steps)
- [License](#license)
- [Author Info](#author-info)

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

---

## Executive Summary

The tech industry moves fast, and staying relevant means knowing which skills are gaining traction and where opportunities are concentrated. This project combines job posting data (via API), salary tables (via web scraping), and survey results to identify which programming languages and technologies are most in demand, how salaries compare, and where the top markets are located. By integrating multiple data sources, the analysis highlights actionable insights for recruiters, job seekers, and educators. In a real-world setting, these insights could **cut** recruiter **time-to-hire by 20%** and help professionals **boost salaries by $10K–$15K** by focusing on high-value skills.Potential next steps include building an automated pipeline to track job market shifts in real time.

- **Current Technologies**
![Current Technologies](/images/dashboard-images/CurrentTechnologies.png)

- **Demographics**
![Demographics](/images/dashboard-images/Demographics.png)

- **Future Technologies**
![Future Technologies](/images/dashboard-images/FutureTechnologies.png)

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

---

## Business Problem

Recruiters struggle to match talent with rapidly shifting technology needs, while professionals risk investing time in skills that may not pay off. Companies also want to benchmark salaries to remain competitive. The challenge: sift through fragmented data sources (job boards, surveys, salary tables) and distill a clear view of in-demand skills, high-paying languages, and geographic hot spots. This project addresses that gap by merging structured and unstructured data into a coherent, decision-ready analysis.

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

---

## Methodology  

1. **Data Collection:**
   - Extracted job postings and skills from JSON API.
   - Scraped salary data from public HTML tables.
   - Processed survey CSVs covering demographics and tech adoption.

2. **Data Processing:**
   - Normalized survey responses using pandas.
   - Cleaned and structured salary data with BeautifulSoup.
   - Engineered features for programming language demand and salary mapping.

3. **Analysis & Visualization:**
   - Python (matplotlib) for job/salary breakdowns.
   - Power BI dashboards to compare current vs. future tech usage.
   - Presentation slides for stakeholder-ready insights.

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

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

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

---

## Skills

- **Python:** pandas (data cleaning), requests (API extraction), BeautifulSoup (web scraping), matplotlib (visualization)
- **Power BI:** dashboards, comparative analysis, survey insights
- **Data Integration:** combining API, web, and survey datasets into one view
- **Presentation:** translating analytics into stakeholder-friendly visuals

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

---

## Results and Business Recommendation  

- **Most In-Demand Skills:** Python, SQL, and TypeScript dominated job postings.
- **High-Value Skills:** Swift and Python commanded average salaries above **$120K**.
- **Market Hotspots:** Washington DC and Detroit emerged as leading tech job hubs.
- **Survey Insights:** Highlighted gaps between current vs. future tech adoption, useful for planning workforce training.

**Recommendation:** Recruiters should double down on sourcing Python and SQL talent while expanding pipelines in cities with growing demand. Training providers should focus on future-oriented skills like Swift and TypeScript to stay ahead of demand.

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

---

## Project Files

The following are the files in this project:

- [Survey Data](data/m5_survey_data_technologies_normalised.csv)
- [Survey Demographics Data](data/m5_survey_data_demographics.csv)
- [Microsoft Power BI Report](TechJobsSurveyReport.pbix)
- [Microsoft Powerpoint Presentation](TechJobsSurveyPresentation.pptx)
- [Jupyter Notebook for Survey Analysis](TechJobsSurveyAnalysis.ipynb)
- [Jupyter Notebook for Salary Analysis](TechJobsSalaryAnalysis.ipynb)

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

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

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

---

## Next Steps  

If expanded, this project could:
- Automate job market tracking via scheduled API/web scraping pipelines.
- Add LinkedIn/Indeed datasets for broader coverage.
- Model demand-supply gaps to forecast salary growth.
- Track how demand for emerging skills (AI/ML tools, cloud platforms) evolves quarterly.
- Address data limitations such as inconsistent salary reporting and incomplete job postings.

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

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

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)

---

## Author Info

- Github - [Github Profile](https://github.com/prasanna-sriram)
- LinkedIn - [Prasanna Sriram](https://www.linkedin.com/in/prasanna-sriram/)
- Tableau - [Tableau Public Profile](https://public.tableau.com/app/profile/prasanna.sriram.ps)

[Back to the Top](#tech-job-market-trends-analysis-with-python-web-scraping-and-power-bi)