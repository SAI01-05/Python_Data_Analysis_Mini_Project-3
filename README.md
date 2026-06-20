# Netflix Stock Analysis Using Python

A data analysis project exploring Netflix Inc. (NFLX) historical stock data using Python. The project covers stock price trends, trading volume patterns, and identification of peak and lowest price dates across a ~20-year period from 2002 to 2021.

---

## Dataset

**File:** `Netflix.csv`  
**Records:** 4,874 rows  
**Date Range:** May 2002 to September 2021  
**Source:** Netflix Inc. (NFLX) historical stock data

**Columns:**

| Column     | Description                          |
|------------|--------------------------------------|
| Date       | Trading date                         |
| Open       | Opening price of the stock           |
| High       | Highest price during the trading day |
| Low        | Lowest price during the trading day  |
| Close      | Closing price of the stock           |
| Adj Close  | Adjusted closing price               |
| Volume     | Number of shares traded              |

---

## Tools and Libraries

- Python 3.x
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Jupyter Notebook

---

## Analysis Overview

### 1. Volume of Stock Traded Over Time
Line plot visualizing how trading volume changed across the entire timeline.

![Volume of Stock Traded Over Time](https://YOUR_IMAGE_LINK_HERE/volume_over_time.png)

---

### 2. Stock Price Trend (High, Open, Close)
Multi-line plot comparing the High, Open, and Close prices of Netflix stock across the full date range.

![Netflix Stock Price High Open Close](https://YOUR_IMAGE_LINK_HERE/stock_price_trend.png)

---

### 3. Day, Month, and Year-Wise Volume Analysis
Three-panel chart showing average trading volume broken down by day of month, month of year, and year — to identify seasonal and long-term patterns.

![Day Month Year Wise Volume](https://YOUR_IMAGE_LINK_HERE/day_month_year_volume.png)

---

### 4. Top 5 Dates with Highest Stock Price
Tabular output and analysis identifying the five trading days that recorded the highest stock prices in the dataset.

![Top 5 Highest Stock Prices](https://YOUR_IMAGE_LINK_HERE/top5_high.png)

---

### 5. Top 5 Dates with Lowest Stock Price
Tabular output identifying the five trading days with the lowest recorded stock prices — correlating to early 2002 post-IPO trading.

![Top 5 Lowest Stock Prices](https://YOUR_IMAGE_LINK_HERE/top5_low.png)

---

### 6. High vs Low Price Comparison
Side-by-side line plots comparing the High (green) and Low (red) stock values over the full period to visualize overall price growth and volatility.

![High and Low Stock Price Comparison](https://YOUR_IMAGE_LINK_HERE/high_low_comparison.png)

---

## Key Findings

- Netflix stock showed consistent long-term growth from under $2 in 2002 to over $600 by late 2021.
- Trading volume was significantly higher in the early years and gradually normalized as the stock matured.
- The highest stock prices were recorded in late 2021, while the lowest were in mid-2002, shortly after the IPO.
- Monthly and yearly breakdowns reveal that volume spikes often correlate with major company announcements and earnings periods.

---


---

## Project Structure

```
netflix-stock-analysis-python/
|-- Netflix.csv
|-- Netflix_Stock_Analysis_Using_Python.ipynb
|-- README.md
```

---

## Skills Demonstrated

- Data cleaning and datetime parsing with Pandas
- Time-series indexing and groupby aggregations
- Multi-panel data visualization using Matplotlib and Seaborn
- Exploratory Data Analysis (EDA) on financial datasets
- Jupyter Notebook documentation

---

## Author

**Sai Halwai**  
B.Sc. Computer Science (Game Design and Development)  
GitHub: [SAI01-05](https://github.com/SAI01-05)  
Email: saihalwai01@gmail.com  

