### Google Query Project

---

### Overview
 
This project designed to gain practical experience with google query sheets, Query syntax, an essential resource for data filtering, data sorting, data aggregation and data joining. This repository provides a collection of sample datasets and examples to help users master the QUERY functions in google sheets, unlocking advanced data analysis capabilities. 

---

### Table of Contents

---

- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Data Source](#data-source)
- [Tools Used](#tools-used)
- [Usage](#usage)
  - [Example Queries](#example-queries)
- [Findings and Insights](#findings-and-insights)
- [Conclusion](#conclusion)

---

### Features

---

- Data Filtering: This involves selecting a subset of data based on specific criteria. For example, you might want to view only sales data for a certain year or customers in a specific region. Filtering helps narrow down large datasets to focus on relevant information.

- Data Sorting: Sorting arranges data in a particular order, usually ascending or descending. For instance, you can sort customer data by name alphabetically or sort transactions by date. Sorting makes it easier to analyze and find patterns within the data.
  
- Data Aggregation: Aggregation combines multiple rows of data into summary values. Common aggregations include sums, averages, counts, minimum, and maximum values. For example, you could aggregate sales data to find the total revenue per month, which simplifies large datasets into meaningful insights.
  
- Logical Operations: Logical operations use conditions to compare values and return results based on true or false outcomes. Common logical operators include AND, OR, and NOT. For instance, you might use logical operations to filter data where both sales exceed $2,000 and the customer is in a specific region.
  
- Data Transformation: Data transformation modifies data into a new format or structure. This might involve converting data types, normalizing (scaling) values, or changing the layout. Transformation is essential when preparing data for analysis, as it ensures that data is consistent and ready for further processing

---

### Getting Started

---

 git clone https://github.com/RuthOkorie/Google-Query-Project/edit/main/README.md

---

### Data Source

---

The dataset used in this project is a sales record from Skillharvest, detailing essential information such as regions, sales representatives, items sold, order dates, and total sales. This dataset provides a solid foundation for analyzing sales performance across different dimensions, offering insights into regional trends, sales rep efficiency, and product demand. It's a free  online dataset. [Download Here](https://docs.google.com/spreadsheets/d/14PAdrDS1FkJNgUKe2W7TKwXkZ2HzL5nwG_mItqNXSEE/edit?gid=1710517431#gid=1710517431) 

---

### Tools Used

---

Google Sheets: The primary tool used for data manipulation, filtering, and aggregation.

Google Sheets QUERY Function: Utilized for efficient data extraction, filtering, sorting, and aggregation.

GitHub: Used for sharing and documenting the project, with visual examples and code snippets included for clarity.

---
### Usage
---
In this section, I’ve included images of the dataset and highlighted key data points to showcase the use of the QUERY function in Google Sheets. Each example demonstrates practical applications for data manipulation, filtering, and aggregation using QUERY, making it easy to extract meaningful insights from complex data.

---
### Queries Exmaple
---

 ![Main sheet](https://github.com/user-attachments/assets/fdada2f8-4dd5-46bb-905b-13a5407a77a6)
  
   This image shows the  dataset used in these examples.

### Example one QUERY Function

1.  ![Screenshot 2024-11-14 134745](https://github.com/user-attachments/assets/2fbd8f27-ebef-4574-a5df-1ad1dac9f749)
 - i. The Region, Sales_rep, and Sales Data Point was extracted using the following Query function;

   = QUERY(A:H, "SELECT A, B, H",1)


 













