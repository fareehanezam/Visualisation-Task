# Visualisation-Task
Visualization of the UCI Online Retail dataset to uncover sales trends and customer behavior. This project uses Python for RFM analysis, K-Means clustering, and PCA to create actionable customer segments.

Here's the content for a `README.md` file for your e-commerce data analysis project.

-----

# E-Commerce Customer Behavior Analysis 🛍️

This project performs an in-depth Exploratory Data Analysis (EDA) on the "Online Retail" dataset from the UCI Machine Learning Repository. The goal is to uncover insights into sales patterns, customer purchasing behavior, and geographic trends using various data visualization and machine learning techniques.

-----

## 📊 Dataset

The analysis is based on the **Online Retail Dataset**, which contains transactional data for a UK-based online retail company from December 1, 2010, to December 9, 2011.

  * **Source:** [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/online+retail)
  * **Characteristics:** The dataset contains 541,909 instances with 8 attributes, including:
      * `InvoiceNo`: A unique identifier for each transaction.
      * `StockCode`: A unique identifier for each product.
      * `Description`: The name of the product.
      * `Quantity`: The number of units of a product per transaction.
      * `InvoiceDate`: The date and time of the transaction.
      * `UnitPrice`: The price per unit of the product in pounds sterling (£).
      * `CustomerID`: A unique identifier for each customer.
      * `Country`: The country where the customer resides.

-----

## Graphs ScreenShot
<img width="1548" height="525" alt="newplot (1)" src="https://github.com/user-attachments/assets/a8b15fbe-4885-433c-b9d3-85300e61149b" />
<img width="1537" height="525" alt="newplot (2)" src="https://github.com/user-attachments/assets/0489fa39-7198-495a-a863-4acbb2aa5c98" />
<img width="1537" height="525" alt="newplot (3)" src="https://github.com/user-attachments/assets/8c2e0294-347b-453b-8493-31681e59bc46" />
<img width="1548" height="525" alt="newplot (4)" src="https://github.com/user-attachments/assets/b0e9239d-5c24-4fa5-93c2-3c84d9469c46" />
<img width="1548" height="525" alt="newplot (5)" src="https://github.com/user-attachments/assets/aea3c511-5386-407e-869e-0ae7d905a2cf" />
<img width="1548" height="525" alt="newplot (6)" src="https://github.com/user-attachments/assets/a61c352c-22cc-4f8a-b98e-c984ced4f272" />

------
## 💡 Key Insights

The analysis revealed several actionable insights:

  * **Seasonal Peaks:** Sales show a strong upward trend throughout the year, with a significant spike in **November**, likely due to holiday shopping.
  * **Prime Shopping Hours:** The busiest shopping period is during weekdays from **12 PM to 3 PM**.
  * **Dominant Market:** The **United Kingdom** is the primary market, accounting for the vast majority of sales.
  * **Customer Segments:** Customers can be clearly grouped into segments (e.g., high-value, loyal, at-risk), allowing for targeted marketing strategies.



## 
    ```

4.  **Open the `ecommerce_visualization.ipynb` file and run the cells sequentially.** The notebook fetches the data directly from the online source, so no manual download is required.
