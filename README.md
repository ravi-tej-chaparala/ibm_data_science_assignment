# Stock Price and Revenue Analysis Assignment

## Assignment Overview

This assignment involves extracting and analyzing stock price and revenue data for Tesla and GameStop using Python. The task is divided into multiple sections, where stock data is retrieved using the `yfinance` library, revenue data is scraped from webpages, and both datasets are visualized with graphs.

### Key Tasks:
1. **Extract Stock Data using yfinance**: 
   - Retrieve historical stock prices for Tesla and GameStop.
   - Save the data in dataframes and preprocess it for analysis.

2. **Web Scraping for Revenue Data**: 
   - Scrape quarterly revenue data for Tesla and GameStop from specified URLs using `requests` and `BeautifulSoup`.
   - Clean and preprocess the revenue data.

3. **Data Visualization**:
   - Use the provided `make_graph` function to plot the historical stock prices and revenue data for both Tesla and GameStop.
   - Generate insightful visualizations that help in understanding the trends in stock prices and revenue over time.

### Technologies Used:
- **Python**: The primary programming language for this assignment.
- **yfinance**: Used to extract stock data.
- **BeautifulSoup**: Used for web scraping the revenue data.
- **Plotly**: Employed for visualizing the stock and revenue data.

### Steps Involved:
1. Install necessary libraries (`yfinance`, `BeautifulSoup`, `plotly`, etc.).
2. Extract stock data for Tesla (TSLA) and GameStop (GME) using `yfinance`.
3. Web scrape Tesla and GameStop revenue data using `requests` and `BeautifulSoup`.
4. Visualize the data using the `make_graph` function, plotting historical stock prices and revenue for both companies.

### Key Functions:
- **`make_graph(stock_data, revenue_data, stock)`**: A function to plot two graphs (historical share price and historical revenue) for the specified stock.

### Conclusion:
This assignment demonstrates how to retrieve, clean, and visualize stock and revenue data using Python. It highlights key skills in data extraction, web scraping, and data visualization, providing valuable insights into the financial performance of Tesla and GameStop.

