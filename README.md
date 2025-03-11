# COVID-19 vs. Canadian Stock Market Analysis

## Project Overview
This project analyzes the impact of COVID-19 on the Canadian stock market. By examining COVID-19 dataset statistics across Canadian provinces and territories alongside stock market performance data, we aim to uncover trends, correlations, and the pandemic's effects on market activity and recovery.

## Team Members
- Puja Shrestha  
- Kelvin Krisna de Rodrigues Silva  
- Karan Maheshbhai Mistry  

## Datasets Used
### 1. Canada COVID-19 Data
- **Source:** [COVID-19 Data Worldwide](https://www.kaggle.com/datasets/kunwarakash/covid19-cleaned-data-worldwide?select=Covid+datasets.csv)
- **Size:** 8,752 rows, 8 columns
- **Use Case:** Tracking COVID-19 trends and analyzing its impact across different provinces

### 2. Canada Stock Market Data
- **Source:** Yahoo Finance (Yfinance Library)
- **Stocks Analyzed:** ^GSPTSE, BNS.TO, WCP.TO, SES.TO, POW.TO, ENGH.TO, RUS.TO, IAG.TO, FC.TO, CNQ.TO, RY.TO
- **Size:** 18,852 rows, 8 columns
- **Use Case:** Analyzing stock performance and volume data

## Data Preparation and Cleaning
- Extracted relevant COVID-19 data for Canada
- Retrieved stock data using the Yfinance library
- Included asset names for each stock
- Standardized date formats
- Removed unnecessary columns (e.g., unnamed index columns)

## Key Research Questions
1. Which province had the highest number of COVID-19 cases?
2. How was the stock market affected by COVID-19?
3. How did transaction volumes change during the pandemic?
4. How did different stocks recover during and after COVID-19?

## Analysis Performed
- **Total Cases by Province**: Visualization of the distribution of cases across Canada
- **Percentage of Cases by Province Population**: Comparison of COVID-19 spread relative to population size
- **Maximum New Cases Daily by Province**: Identifying peak infection rates
- **Stock Price Variation**: Examining fluctuations in stock prices due to COVID-19
- **Volume of Transactions**: Evaluating market activity changes
- **S&P/TSX Composite Index Performance**: Tracking overall market trends

## Notable Stocks Analyzed
- **CNQ (Canadian Natural Resources Limited)** – Energy sector
- **FC (Firm Capital Mortgage Investment Corp)** – Financial services
- **RY (Royal Bank of Canada)** – Banking sector
- **ENGH (Enghouse Systems Limited)** – Technology sector
- **SHOP (Shopify Inc.)** – Technology sector

## Key Findings
- All provinces in Canada were significantly affected by COVID-19.
- The stock market reacted more to fear than the actual economic consequences of the pandemic.
- Technology companies saw increased investment despite the market downturn.
- After the initial impact, transaction volumes increased as investors sought profit opportunities and recovery strategies.

## Conclusion
The COVID-19 pandemic had a significant impact on the Canadian stock market, affecting different sectors in varied ways. While some industries suffered, others, particularly technology, saw substantial growth. The market initially declined due to uncertainty but later showed signs of recovery with increased trading activity.

## Repository Structure
```
|-- data/                     # Raw datasets used in the analysis
|-- notebooks/                # Jupyter notebooks containing data analysis
|-- reports/                  # Presentation and findings
|-- src/                      # Source code for data processing and visualization
|-- README.md                 # Project documentation
```

## How to Run the Analysis
1. Clone the repository.
2. Run the Jupyter Notebook (`Data Analysis.ipynb`) to generate visualizations and insights.
3. Review the final presentation (`Final Presentation.pptx`) for summarized findings.

## Acknowledgments
- Data sourced from [COVID-19 Data Worldwide](https://www.kaggle.com/datasets/kunwarakash/covid19-cleaned-data-worldwide?select=Covid+datasets.csv) and Yahoo Finance.
- Libraries used: Pandas, Matplotlib, Seaborn, Yfinance.

For any queries, feel free to reach out!


