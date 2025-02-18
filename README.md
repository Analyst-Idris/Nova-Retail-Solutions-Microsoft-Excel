# Microsoft-Excel-Nova-Retail-Solutions Analysis

![Image](https://github.com/user-attachments/assets/e519e819-7576-4270-b4f8-94cbe4ddc407)

## Introduction:

Nova Retail Solutions is a dynamic retail company that offers quality products in categories such as Beauty, Clothing, and Electronics. The company aims to enhance customer satisfaction and business efficiency by leveraging data-driven insights. Focusing on understanding customer demographics, product performance, and sales trends, Nova Retail Solutions seeks to optimize operations, improve marketing strategies, and drive profitability.


## Objectives of the Project:


**1.	Analyze Customer Demographics:** To understand the distribution of transactions by age bracket and gender, enabling Nova Retail Solutions to effectively tailor marketing campaigns to specific customer groups.


   
**2.	Evaluate Product Performance:** To identify sales contributions from key product categories (Beauty, Clothing, Electronics) and assess their profitability to prioritize high-performing products.
   
   
  
**4.	Monitor Weekly and Monthly Sales Trends:** To uncover transaction patterns by weekday and  month, helping optimize store operations, staffing, and promotional strategies.


	
**5.	Key Metrics Tracking:** To provide an overview of essential business metrics, including total sales, units sold, and average price, for measuring overall business performance and guiding strategic decisions.




## Data Exploration:

**1. Transaction ID:** A unique identifier assigned to each sales transaction for tracking and reference.
   
**2. Date:** The specific date on which the transaction took place.
   
**3. Customer ID:** A unique identifier assigned to each customer to differentiate individual buyers.
 
**4. Gender:**  The gender of the customer who made the purchase.

**5. Age:** The age of the customer at the time of the transaction.
 
**6. Product Category:** The type of product purchased, categorized as Beauty, Clothing, or Electronics.

**7. Quantity:** The number of units of the product bought in the transaction.
 
**8. Price per Unit:** The cost of a single unit of the purchased product.
   
**9. Total Amount:**  The total value of the transaction.


## Methodology

### Data preparation and Visualization:

To ensure accurate and insightful analysis, the dataset underwent a thorough cleaning and manipulation process, improving its accuracy, consistency, and usability. The key steps taken include:

**Handling Missing Data** – Empty cells were replaced with appropriate values to maintain data integrity. For numerical fields, missing values were imputed using reasonable estimates, and categorical fields were filled based on logical assumptions.

**Structuring Age Groups** – Instead of analyzing individual ages, customers were grouped into age brackets (e.g., 18–29, 30–39, 40–49, 50–64). This helped in identifying the purchasing behavior of different demographic groups.

**Extracting Date Attributes** – The Date column was transformed to extract meaningful time-based insights:

**1. Year** – Transactions were categorized by year (e.g., 2023, 2024) to track annual sales trends.
   
**2. Month** – Sales were aggregated by month (e.g., January, February) to analyze monthly sales trends and identify peak and low-performing months.
   
**3. Quarter** – Data was grouped into Q1, Q2, Q3, and Q4 to observe quarterly performance.
   
**4. Weekday & WeekType** – Transactions were classified into weekdays and weekends, allowing the analysis of customer behavior based on different days of the week.

**5. Categorizing Product Types** – Product categories were standardized into Beauty, Clothing, and Electronics, ensuring consistent classification across transactions.

 ## Preview of data before cleaning:

![Image](https://github.com/user-attachments/assets/819b708e-0fb7-4b17-ad69-0208b816cdfc)

## Preview of data after cleaning  and manipulation in table form:

![Image](https://github.com/user-attachments/assets/7397abde-d5f8-41ce-9d7d-09d8c6904206)

## Pivot Table:

![Image](https://github.com/user-attachments/assets/0646b273-4613-4a3c-b4af-9200a05521c0)

## Key Performance Indicators:

![Image](https://github.com/user-attachments/assets/f2a8f58a-00d0-40ef-bb96-ce4e8ac7f6d5)

## Slicer:

![Image](https://github.com/user-attachments/assets/513fe750-2203-4476-a516-700ad65ba967)

# Visualization:

![Image](https://github.com/user-attachments/assets/ee32cb25-2f52-4513-bb39-34d12cfd2b9c)




![Image](https://github.com/user-attachments/assets/2f8d670e-3552-4370-ad20-33198c12606d)



# Insights from the Retail Sales Review Dashboard:

## 1.	Overall Performance Metrics
   
o	The total number of transactions recorded is **1,000**.

o	The total sales revenue stands at **$456k**.

o	A total of **2,514** units were sold.

o	The average price per unit is **$179.8**.


## 2.	Transaction Trends:

## o	Transactions by Week Type:
	Weekday transactions (712) significantly outnumber weekend transactions (288), indicating that most sales occur during the weekdays.

#### o	Transactions by Weekday:
	Tuesday has the highest number of transactions (161), while Thursday has the lowest (123).

## 3.	Demographic Analysis:

### o	Transactions by Age Bracket:
	The **50–64 age group** has the highest number of transactions (336), suggesting that older customers are more engaged in purchases.

	The **18–29 age group** follows with 251 transactions, while the **30–39 group** has the lowest at 191.

### o	Transaction by Gender:

	**Females (61%)** make up a larger share of transactions compared to **males (39%)**, suggesting a stronger purchasing tendency among female customers.


## 4.	Product Category Performance:

o	The sales distribution across different product categories is relatively balanced:

	**Beauty products:** 157k sales

	**Clothing:** 156k sales

	**Electronics:** 144k sales


## 5.	Monthly Sales Performance:

o	Sales peaked in **April ($53k)** and **October ($47k)**, possibly due to seasonal demand or promotions.

o	The lowest sales month was **August ($24k)**, indicating a potential slow period for the business.

o	Other months fluctuated between $29k and $45k, showing moderate performance.





