# Sales Data Analysis

A Python-based project analyzing sales data to extract meaningful insights, such as identifying the best month for sales, top-performing cities, optimal advertisement timing, and products often sold together.

---

## Questions Solved:
1. **What was the best month for sales?**  
   **Answer:** December was the best month for sales, with total earnings of over **$4,6 mil**.

![Best Month for Sales](./SalesAnalysis/plots/output1.png)

2. **What city had the highest number of sales?**  
   **Answer:** San Francisco had the highest number of sales, making it the top-performing city.
            
               
![Top City](./SalesAnalysis/plots/output2.png)


3. **What time should we display advertisements to maximize the likelihood of customers buying products?**  
   **Answer:** The optimal advertisement times are around **11 AM** and **7 PM**, when customer purchase activity peaks. Unusually high average sales in the early hours, possibly due to online shoppers in different time zones or late-night impulse buying. After work hours (~7pm), there's another surge in purchases when customers are more relaxed and have free time.

![Hourly Sales Sum](./SalesAnalysis/plots/output3.png)

![Hourly Sales Avg](./SalesAnalysis/plots/output4.png)


4. **What products are most often sold together?**  
   **Answer:** The most common product combination sold together is **iPhone** and **Lightning Charging Cable**, followed by **Google Phone** and **USB-C Cable**.

![Top Products Bought Tgether](./SalesAnalysis/plots/output6.png)

---

## Dataset
- The dataset contains sales records including **order ID, product, quantity ordered, price, order date, purchase address, etc.**
- Data preprocessing includes:
  - Handling missing values
  - Parsing dates
  - Extracting useful features (e.g., month, city, purchase hour)
  - Identifying product combinations

---

### Credits

- **Dataset and Questions:** Provided by [Keith Galli](https://www.youtube.com/watch?v=eMOA1pPVUc4&t=4721s)  
- **Solutions:** Implemented by me