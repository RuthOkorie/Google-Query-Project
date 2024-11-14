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
- [Queries Example](#queries-example)
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
### Queries Example
---

 ![Main sheet](https://github.com/user-attachments/assets/fdada2f8-4dd5-46bb-905b-13a5407a77a6)
  
   **This image shows the  dataset used in these examples**

### Example one QUERY Function

1.  ![Screenshot 2024-11-14 134745](https://github.com/user-attachments/assets/2fbd8f27-ebef-4574-a5df-1ad1dac9f749)

    **This image shows the two data points extracted using the QUERY functions below**
    
 - i. The Region, Sales_rep, and Sales Data Point was extracted using the following Query function;

   ```
      = QUERY(A:H, "SELECT A, B, H", 1)
   ```

 - ii. The Item and Year Data Point was extracted using the following Query function;
     
   ```
      = QUERY(A:H,"SELECT C, F",1)
   ```

---

2.  ![Screenshot 2024-11-14 135020](https://github.com/user-attachments/assets/7deb17ff-a775-4c75-a556-1e992132b914)
  
    **This image shows the two data points extracted using the QUERY functions below**
    
  - i. The Month and Year Data Point was extracted using the following Query function;

    ```
      = QUERY(A:H,"SELECT E, F", 1)
    ```

   - ii. The Sales_rep, Item and OrderDate was extracted using the following Query function;

     ```
       = QUERY(B:D, "SELECT B, C, D",1)
     ```
---  

3.  ![Screenshot 2024-11-14 135112](https://github.com/user-attachments/assets/ab7f3c1c-19ae-489f-8ad6-7c63b3de7719)
4.  
    **This image shows the two data points extracted using the QUERY functions below**
    
  - i. The Region and Sales Data Point, where Sales is less than 100 was extracted using the following Query function;

     ```
       = QUERY((A:H,"SELECT A,H WHERE H>100")
     ```
     
  - ii. The Region, Item and Year, where Year is equals 2014 was extracted using the following Query function;

     ```
       = QUERY(A:H,"SELECT A,C,F WHERE F=2014")
    ```
---

4. ![Screenshot 2024-11-14 135621](https://github.com/user-attachments/assets/aafb3971-4ffc-4431-8a1a-8cc19f62ce53)
  
   **This image shows the two data points extracted using the QUERY functions below**
   
  - i. The Sales that happened in 2015 and their Region was extracted using the following Query function;

     ```
       = QUERY(A:H,"SELECT A, F ,H WHERE F=2015",1)
     ```
  - ii. The Sales of Items that is not 825 or 250 was calculated using the following Query function;

     ```
       = QUERY(A:H,"SELECT C, H WHERE H<>825 AND H<>250",1)
     ```
---

5. ![pic](https://github.com/user-attachments/assets/10efd59a-ee64-4a70-a77f-045dc7a81c43)

   **This image shows the two data points extracted using the QUERY functions below**
   
  - i. The Region, Sales_rep and Sales where Region equals East or West was calculated using the following Query function;

     ```
       = QUERY(A:H,"SELECT A,B,H WHERE A= 'East' OR A= 'West'",1)
     ```
---

### Findings and Insights

---
   jh
   




