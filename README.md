# Final Project - Python-Module

## 📌 About This Project
This project focuses on **analyzing data from the website www.sreality.cz**. The goal is to retrieve and process the current apartment listings in Zlín, perform data analysis, and answer key questions.

## 🔍 Project Structure

### 1️⃣ Web Scraping 🕵️‍♂️
We will use **BeautifulSoup** to extract the following details for each listed apartment:
- **Apartment URL**
- **Apartment size**
- **Apartment layout (e.g., 2+1, 3+kk, etc.)**
- **Apartment price**
- **Location (Street + City)**

### 2️⃣ Data Analysis - ETL Process 📊
- Process the data to ensure **correct data types and no missing values**.
- Store street and city information in separate columns.
- Export the processed and cleaned data as a **CSV file** named `{yourName}_source_data.csv`.

### 3️⃣ Data Analysis - Insights & Visualization 📈
In the third part, we will analyze the collected data and answer these questions:
- **What is the average apartment price?**
- **What is the average price per apartment layout (e.g., 1+1, 2+1, etc.)?** *(visualized in a graph)*
- **What is the average apartment size for each layout?**
- **Is there a street with a higher concentration of expensive apartments?**
- **Which apartment layout is the most frequently listed? Why do you think that is?**
- **Are there apartments priced above 20,000 CZK? If so, are 2+1 or 2+kk apartments included in this price range?**
- **What is the minimum and maximum price for each layout? Which layout has the biggest price range?**

## 📂 Project Deliverables
- **Raw and cleaned `.csv` files**
- **Notebook containing the analysis and answers to the questions**
- **Graphical visualizations supporting the results**

## Resources
- [BeautifulSoup Documentation](https://www.crummy.com/software/BeautifulSoup/bs4/doc/)
- [Pandas Documentation](https://pandas.pydata.org/docs/)
- [Matplotlib Documentation](https://matplotlib.org/stable/contents.html)

 **Happy scraping & analyzing!**

