
# Financial Chatbot Prototype

## Description
A minimal chatbot that answers predefined financial queries for Apple, Microsoft, and Tesla using data from `financial_data.csv`.

## Supported Queries
- What is the total revenue for <company>?
- How has net income changed over the last year for <company>?
- Which company had the highest recent revenue growth?
- What is the cash flow from operating activities for <company>?

## How to Run in Jupyter Notebook
1. Place `financial_data.csv` in the same folder as this notebook.
2. Open the notebook in Jupyter.
3. Run all cells.
4. Use the CLI cell to type questions, or run the optional Flask app cell for a browser interface.

## Data Source
Data comes from `financial_data.csv` with the following columns:
- Company
- Fiscal Year
- Total Revenue (USD B)
- Net Income (USD B)
- Total Assets (USD B)
- Total Liabilities (USD B)
- Cash Flow from Operating Activities (USD B)

## Limitations
- Only answers 4 types of predefined queries.
- Company names must be present in the dataset.
- No live data fetching — answers are static from the CSV.
