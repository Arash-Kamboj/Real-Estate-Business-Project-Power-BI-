# Real-Estate-Business-Project-Power-BI-
----------------------------------------------------------------------------------------------------------------------------------------------------------------------------
Business Case:
In this case study, I delved into a company with diversified ventures across various product ranges and a prominent presence in the real estate sector. As the global business head of the company, I took the initiative to develop a comprehensive dashboard using Power BI to monitor critical metrics related to  nine business unit managers, products, sales, quantities sold, and gross margins (GM).

Steps:

#1 - **Extract, Load, Transform (ELT)**:
I began by downloading the dataset from the provided link **https://drive.google.com/drive/folders/1eplz7vmnNG67KECek0CUAyFaVxm4ngc2?usp=sharing**
and initiated the Extract-Load-Transform (ELT) process. Leveraging Power BI's capabilities, I extracted the data, loaded it into the Power BI environment, and meticulously transformed it. Using Power Query Editor, I cleaned unused or erroneous rows, rectified datatype discrepancies, and resolved any other data-related issues to ensure data accuracy and consistency.

#2 - **Data Modeling**:
Given the normalized database structure, with multiple tables representing distinct data points, I utilized Power BI's data modeling capabilities to establish coherent relationships among these tables. Leveraging Power BI's Relationship View, I defined and managed relationships, ensuring that the final schema reflected a cohesive structure facilitating seamless data interaction.

![Schema ](https://github.com/Arash-Kamboj/Real-Estate-Business-Project-Power-BI-/assets/156613048/fd873750-d33d-40ab-af6f-6aa9a7628ae7)


#3 - **Visual Level Filters with Slicer**:
Utilizing Power BI's visualization tools, I implemented visual level filters using slicers. Leveraging Power BI's Slicer Visualization, I configured slicers with multi-selection options and included a "Select All" option, enhancing user flexibility and analytical depth.

#4 - **Donut Chart for Gross Margin Contribution**:
I created a donut chart, visually representing the percentage contribution of Gross Margin to Total Gross Margin. Leveraging **Power BI's DAX** (Data Analysis Expressions) language, I computed Total Sales using the **Total Sales =  (Sum_Markdown_Sales_Dollars * Sum_Markdown_Sales_Units) + (Sum_Regular_Sales_Dollars * Sum_Regular_Sales_Units)** formula, incorporating both markdown and regular sales data.

#5 - **Revenue and Expense Analysis**:
Leveraging Power BI's analytical capabilities, I conducted a comprehensive analysis of revenue and expenses. Using DAX functions, I calculated Total Quantity (Units) by aggregating markdown and regular sales units. Focusing on the 'Home category' for high-margin transactions, I identified home sales with a gross margin exceeding 10% using Power BI's filtering and conditional formatting features.

#6 - **Table Chart for Gross Margin Scenarios**:
Developed a table chart, presenting the sum of Gross Margin for two distinct scenarios based on sales data. Leveraging DAX language, I computed the Gross Percentage, indicating the proportion of Gross Margin attributed to Scenario 1 transactions.

#7 - **Drill Down Capability for Rent Analysis**:
Utilizing Power BI's drill-down capabilities, I implemented a hierarchical structure ranging from Year to Quarter to Month levels for analyzing total rent obtained over time. I plotted charts with interactive drill-down functionality, enabling in-depth analysis and visualization.

The developed dashboard aims to offer actionable insights and facilitate informed decision-making for the company's leadership and stakeholders.

![Real State Busniess project ](https://github.com/Arash-Kamboj/Real-Estate-Business-Project-Power-BI-/assets/156613048/78460da7-917b-4e15-9e1a-ef7167aa85c4)




------------------------------------------------------------------------------------------------------------------------------------------------------------------------




