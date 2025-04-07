# Excel Coffee Sales Dashboard
![ScreenRecording2025-04-07170833-ezgif com-video-to-gif-converter](https://github.com/user-attachments/assets/a6bac1f3-07da-45db-a692-198cce5aac89)
## Introduction  
This Coffee Sales Dashboard was created to provide a visual overview of key sales performance indicators over time, across different product attributes, and by customer.
## Dashboard File  
My final dashboard is in [Coffee Sales Analysis.xlsx](https://github.com/nishi-uthappa/Coffee-Sales-Analysis/blob/main/Coffee%20Sales%20Analysis%20Excel%20Project.xlsx)
## Excel Skills Used  
📉 Charts
🧮 Formulas and Functions
❎ Data Validation  
📊 Pivot Tables
📈 Pivot Charts
🧮 DAX (Data Analysis Expressions)
🔍 Power Query
💪 Power Pivot
## Steps Involved  
### 📥 Extract  
I first used Power Query to extract the original data (coffee_sales_dataset.xlsx) and create three queries:
- First one with all the customer data
- The second was all the order data
- The third one was all the product data
### 🔄 Transform  
Then, I transformed each query by changing column types, removing unnecessary columns, cleaning text to eliminate specific words, duplicates and trimming excess whitespace.
### 🔗 Load  
Finally, I loaded both transformed queries into the workbook, setting the foundation for my subsequent analysis.
### 🔗 Data Model  
I created a data model by integrating the different tables into one model. Since I had already cleaned the data using Power Query; Power Pivot created a relationship between tables.
The Power Pivot menu was used to refine my data model to make it easy to create measures.
### 📈 Pivot Tables and Charts  
I then created Pivot Tables and Charts along with key slicers from the measures for final analysis of the data.
### 📊 Dashboard Implementation  
Finally, I created the dashboard which provides a valuable tool for understanding coffee sales performance across key dimensions.  

![Screenshot (39)](https://github.com/user-attachments/assets/9a543fba-7f4c-47dc-93e0-2d6fc46f63db)
## Coffee Sales Dataset  
The dataset used for this project contains real-world data coffee sales information from 2019-2022. The dataset is available here [Coffee Sales Raw Data.xlsx](https://github.com/nishi-uthappa/Coffee-Sales-Analysis/blob/main/Coffee%20Sales%20Analysis%20Excel%20Project.xlsx)

