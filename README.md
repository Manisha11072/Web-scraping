 **Visualizing and Analyzing Largest Companies by Revenue**


 
**Project Overview**

This project gathers data from Wikipedia's list of the largest companies by revenue and performs data cleaning, manipulation, and visualization to derive insights. The goal is to analyze and visualize key business metrics such as revenue, profit, employee size, and market share, offering insights into the financial and operational scales of major global companies.

**Data Collection**
The data is collected from the Wikipedia page on the largest companies by revenue:

**URL**: List of largest companies by revenue
Methods:**** Data is fetched using the requests library, and BeautifulSoup is used to parse the HTML. Table headers and rows are extracted for analysis.
**Data Cleaning**
After extraction, the data undergoes cleaning to prepare it for analysis:

**Column Name Cleaning**: Strips extra spaces and special characters from column names.
**Numeric Conversion:** Removes currency symbols and commas in columns like Revenue and Profit and converts values to floats for accurate analysis.


**Visualizations******
Several visualizations are created using Matplotlib and Seaborn to explore and understand the dataset:

**1.Revenue of the Top Companies**

**Type:** Horizontal Bar Chart
**Palette:** Viridis
**Insight:** Highlights companies with the highest revenue, showing comparisons in revenue size.

**2.Market Share Based on Revenue**
 
**Type:** Pie Chart
**Insight:** Shows each company's market share relative to the total revenue, giving an understanding of the company’s dominance in the market.

**3.Revenue vs Profit**

**Type:** Scatter Plot
**Insight:** Plots revenue against profit to identify the relationship between the two metrics, highlighting companies with high revenue and profit efficiency.

**4.Number of Employees by Company**

**Type:** Horizontal Bar Chart
**Palette:** Blues_r
**Insight:** Visualizes the workforce size across companies, which may correlate with revenue and operational scale.

**5.Revenue and Profit by Company**

**Type:**Grouped Bar Chart
**Palette:** Cool
**Insight:** Compares revenue and profit side-by-side for each company, illustrating profitability relative to revenue.

**Libraries Used**

**Matplotlib:** For general plotting.
**Seaborn**: For enhanced and aesthetic visualizations.
**Pandas**: For data manipulation and cleaning.
**Requests**: For fetching the webpage data.
**BeautifulSoup**: For parsing HTML content and extracting table data.

**Detailed Steps**
**1.Data Cleaning**
Clean column names, remove special characters.
Convert Revenue and Profit columns to numeric after removing currency symbols and commas.

**2.Visualization**
Each visualization type is used to display key metrics and relationships, such as market share, revenue vs. profit, and employee size by company.

**Insights**
-->The visualizations generated from this project provide insights into:
-->Revenue, profit, and market share distributions among top companies.
-->Relationships between revenue, profit, and operational scale.
-->Comparison of revenue and profit margins across companies.


**Conclusion**
By fetching, cleaning, and visualizing data from Wikipedia, this project provides comprehensive insights into the financial and operational metrics of the world’s largest companies. The visualizations enable businesses and stakeholders to analyze key metrics and inform data-driven decisions.


