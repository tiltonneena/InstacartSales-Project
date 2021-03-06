<p align="right">
  <a href="https://tiltonneena.github.io/portfolio/">Back to Portfolio Homepage</a>
</p>

# Instacart Shopping Cart Analysis
### By Neena Tilton
<p align="center">
  <img width="500" height="330" src="Images/instacart.jpg"/>
</p>

### Background

Instacart, an online grocery service that operates through an app, is looking to improve their targeted marketing strategy. To fulfill this goal, the analyst has been tasked with uncovering more information about sales patterns, different purchasing behaviors between customer types, and sales performance of each product. Ultimately, the goal of the project is to perform an analysis to derive insights and suggest strategies for better segmentation. 

### Tools & Context
- **Python:** this programming language was used to perform the bulk of the analysis, including data cleaning, wrangling, subsetting, merging, aggregating, and visualization. 
- **Microsoft Excel:** final report presented in Excel, including analysis methodology, population flows, data visualization, and final recommendations. 
- **Jupyter Notebook:** this web-based interactive computing platform was used for streamlined documentation of all Python scripts.

### Data Source
The data sets (with over 3 million rows) used for this analysis were made available by Instacart. [“The Instacart Online Grocery Shopping Dataset 2017”](https://www.instacart.com/datasets/grocery-shopping-2017) was accessed from the Instacart website on January 14th, 2022.  
 - Click [here](https://github.com/tiltonneena/InstacartProject-Python/tree/main/OriginalData) to download the data sets
 - Click [here](https://gist.github.com/jeremystan/c3b39d947d9b88b3ccff3147dbcf6c6b) to see the data dictionary 
 
### Key Questions 
 - What are the busiest days of the week and hours of the day?
 - What time of day do customers spend the most money? 
 - Which departments have the highest frequency of product orders?
 - Are there differences in ordering habits based on a customer's loyalty status, region, or order frequency? 
 
### Methodology
1. Initial exploratory data analysis performed to first understand the large database, followed by data cleaning, wrangling, and merging. 

    <p align="center">
      <img width="519" height="196" src="Images/pysc_desc.jpg"/>
    </p>
    <p align="center">
      <em>Exploratory analysis was initialized by descriptive analysis.</em>
    </p>
 
    <p align="center">
      <img width="522" height="218" src="Images/pysc_finddups.jpg"/>
    </p>
    <p align="center">
      <em>Duplicated data was located using a filtered subset.</em>
    </p>   

    <p align="center">
      <img width="522" height="40" src="Images/pysc_removedups.jpg"/>
    </p>
    <p align="center">
      <em>Once duplicated data was found, they were cleaned from the<br>main data frame using a built-in Python function.</em>
    </p>

    <p align="center">
      <img width="665" height="209" src="Images/popflowchart.jpg"/>
    </p>
    <p align="center">
      <em>Four separate data sets were merged into one main data frame.</em>
    </p>
    
2. Once the data frame was thoroughly cleaned, new variables were created by derivation and aggregation. 

    <p align="center">
      <img width="522" height="117" src="Images/pysc_dataderi.jpg"/>
    </p>
    <p align="center">
      <em>One of the new variables created categorized<br>products into three pricing types.</em>
    </p>

    <p align="center">
      <img width="522" height="162" src="Images/pysc_dataagg.jpg"/>
    </p>
    <p align="center">
      <em>Newly created categorical variables were<br>aggregated for further insight.</em>
    </p>

3. Data visualizations were created, often using crosstabs for better and easier communication of key findings. 

    <p align="center">
      <img width="400" height="268" src="Images/pyviz_ordertime.jpg"/>
    </p>
    <p align="center">
      <em>Line chart, made in Python, showing the fluctuating<br>prices of items ordered throughout the day.</em>
    </p>

    <p align="center">
      <img width="400" height="265" src="Images/pyviz_income.jpg"/>
    </p>
    <p align="center">
      <em>Bar chart showing the distribution of customers,<br>grouped by income range.</em>
    </p>

4. Finalized a full report of the analysis for the stakeholders in Excel. The report included records of population flow (data set merging), data cleaning/wrangling, newly-derived variables, data visualizations, answers to key questions, and recommendations to inform marketing strategies.   
    
    <p align="center">
      <img width="519" height="540" src="Images/ExcelReport.jpg"/>
    </p>
    <p align="center">
      <em>All data-related questions were answered<br>on the final page of the report.</em>
    </p>

### Key Findings
-	The busiest days of the week were Saturday, Sunday, and Friday.
-	Orders between the hours of 12am and 9am were slow for obvious reasons, however high potential was present to increase sales between 3pm and 9pm. The recommendation was to run advertisements during those hours. 
-	Customer loyalty among the customer base:<br>
      51.3% are Regular customers (10 - 40 orders)<br>
      33.2% are Loyal customers (more than 40 orders)<br>
      15.5% are New customers (less than 10 orders)
-	Regardless of customer loyalty status, most customers were categorically “low spenders” and were frugally-minded. 
-	The department with the highest sales was the produce department. 

### Deliverable
### [Final Stakeholder Report](https://github.com/tiltonneena/InstacartProject-Python/blob/main/Instacart_final_report.xlsx)
 
<p align="center">
  <img width="400" height="285" src="Images/final_image.jpg"/>
</p>
   
<p align="right">
  <a href="https://tiltonneena.github.io/portfolio/">Back to Portfolio Homepage</a>
</p>

 
 
