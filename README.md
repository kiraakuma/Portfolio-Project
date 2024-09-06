# Data Analyst Job Market Analysis in Austria (September 2024)
## Project Overview

This project aims to analyze the Data Analyst job vacancies in Austria in September 2024 by web scraping data from **Indeed** using an open-source parser. The dataset is processed, cleaned, and transformed using **Python**, with further manual review and cleaning in **Excel**. A **Power BI** dashboard was created to visualize key insights, answering the following questions:

1.What is the average salary for Data Analysts?

2.What are the most required technical and soft skills?

3.How does salary depend on experience and location?

4.Which industries employ the most Data Analysts?

5.Which employers have the highest number of vacancies?

### Tools Used

Web Scraping: An open-source parser to extract job data from Indeed.

Data Cleaning & Transformation: Python (pandas, numpy, etc.) for data wrangling.

Data Proofing: Manual review and minor adjustments in Excel.

Data Visualization: Power BI dashboard based on Excel data.

### Process Breakdown

1. Data Scraping
   
I used an open-source parser to scrape Data Analyst job listings from Indeed for September 2024. The scraped data included information such as job titles, salaries, locations, required skills, and experience levels. The scraped data is stored in the file `job_listing.csv`

2. Data Cleaning & Transformation

The scraped data was imported into Python (`main.ipynb`), where I handled missing or inconsistent data by standardizing formats for further analysis. I also extracted the relevant columns, such as job title, salary, location, experience level, skills, industry, and employer, into three different Excel files, which were then merged into a single file, `jobs.xlsx`.

3. Excel Review and Additional Cleaning
   
After exporting the cleaned data to Excel, I performed a final proof by cross-checking outliers and anomalies, manually cleaning any remaining inconsistencies, and calculating key metrics such as mean salary, skill frequency, and other analysis-related values.

4. Data Analysis and Visualization in Power BI

I imported the cleaned Excel file into Power BI to create a simple yet effective dashboard to visualize: Mean Salary of Data Analysts in Austria, Top Required Technical and Soft  Skills, Salary dependence on experience level and location, Popular Industries with the highest demand for Data Analysts and Top Employer with the most job vacancies. The complete overview can be viewed in the `indeed_24_report_analyst.pdf` file.


#### Key Insights

1) Average Salary: While the mean salary for Data Analysts was calculated based on the available job listings, it's important to note that 45% of employers did not provide salary information, making it difficult to assess the true value. Additionally, with only 118 vacancies listed for Data Analysts in Austria on Indeed, the statistical approach may lack precision due to the limited dataset.

2) Required Skills: The results show that technical skills such as Python, SQL, Excel, and data visualization tools are highly demanded, while soft skills like communication and teamwork are highly valued. This data correlates well with broader industry trends, which consistently highlight SQL, Python, and Excel as foundational skills for Data Analysts. Additionally, since around 50% of a Data Analyst's work involves presenting results, it reinforces the importance of communication and teamwork as key soft skills in the role.

3) Salary vs. Experience: Although it's challenging to draw definitive conclusions due to 45% of vacancies lacking salary information, the available data suggests a general trend where more experienced Data Analysts tend to receive higher salaries. However, the incomplete data means there could be inaccuracies, such as junior-level positions appearing to offer higher salaries than mid-level roles. Despite this, the overall trend indicates a potential increase in salary with growing experience.

4) Salary by Location: Major cities exhibit significant variations in salary ranges. In Vienna, where the largest number of vacancies were found, salaries tend to be higher compared to other locations. However, it's important to consider that job postings in other federal states may be more frequently listed on different job portals, which could affect the representation of salary data in these regions.

5) The top industries hiring Data Analysts include IT, retail, and finance, which align with broader industry data. This reflects a consistent trend where these sectors have a high demand for Data Analysts, correlating well with information available from other sources on the internet.

##### Conclusion

This project offers a comprehensive overview of the Data Analyst job market in Austria for September 2024. Despite the limitations—such as the small dataset from Indeed, limited to September, and a significant amount of missing data—the analysis provides valuable insights into salary expectations, required skills, and industry trends. The Power BI dashboard enables stakeholders to interact with the data, facilitating a deeper understanding of the job market.

Although the dataset's constraints may affect the precision of the findings, it still offers a useful snapshot of the Data Analyst job market in Austria. The insights gained from this report have been valuable for my personal job search and can guide further exploration in this field.

