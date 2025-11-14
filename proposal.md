

### Term Project Proposal - (Group - 6)
Group Members:
Jeya Surya Balaji
Nikhil Kumar Korrapati
Shivam Shaileshbhai Patel
Richard Pears
Sivajan Sivarajah

## 1. Business Question:

- What measurable business value can we generate by using machine
learning to forecast mutual fund performance trends?
- How can predictive modeling of mutual fund values enhance our
investment decision-making and improve portfolio returns?

### Explanation (Project View):

This project focuses on developing a predictive model that predicts future
values or benefits of mutual funds using machine learning (ML) techniques.
The goal is to utilize historical financial data to identify patterns and trends
that can predict future return on the securities fund, net wealth (NAV) or
general performance. By using advanced ML algorithms, the project aims
to help investors, financial advisors and fund managers make data-driven
investment decisions, reduce uncertainty and optimize portfolio strategies.

This project can be used by financial institutions, mutual fund companies
and investment advisers:
● Improve forecasts for the fund's result.
● Improve portfolio management and reduce the investment risk.
● Give clients personally, predictive investment insight.
● Strengthen data driven decision making skills.

## 2. Datasets to be Used:
The project utilizes financial datasets obtained through the Yahoo Finance
API, accessed using the yfinance Python library. This library allows
seamless extraction of historical and real-time market data for stocks,
mutual funds, ETFs, and indices.

Using yfinance, we can download key financial information such as Net
Asset Value (NAV), open-high-low-close (OHLC) prices, trading volume,
and adjusted closing prices. These datasets serve as the foundation for
building and training machine learning models to analyze trends and
predict future mutual fund share prices.


In addition, we believe that using the Yahoo Finance Api over any other
website (Bloomberg Api,TSX, etc) that presents stocks would be beneficial
to the investors, as they would be able to get real-time data that will help
them with the decision-making process, especially given that stock prices
may fluctuate alongside market volatility.

Package Link - https://github.com/ranaroussi/yfinance

## 3. High-Level Description of the Dataset:
The Dataset used is from screener available on yahoo finance, the funds
that are considered for this project are shortlisted based on the market cap
of the funds and their tenure. The main dataset will contain OHCLV along
with other financial statements that are queriable from yahoo finances API.
The dataset includes ~5,000 daily observations over 10 years per fund,
with five core variables: Open, High, Low, Close and Volume.

Key variable include:
● Open
● High
● Low
● Close
● Volume


## 4. Similar Projects:

There are several studies and projects that analyze stock and mutual fund
performance using historical financial data, there are some available
projects on public platforms that provide insights on fund performance
metrics.

How our work differs:
Dataset focus: We are using mutual fund and ETF data from Yahoo
Finance, including NAV, OHLCV, and additional financial metrics, rather
than individual stock price prediction.

Business-oriented insights: Our project emphasizes providing actionable
investment insights for decision-making, such as long-term vs short-term
fund suitability, sectoral analysis, and ETF selection.

Machine learning application: We aim to build predictive models that
forecast fund performance, rather than just reporting historical trends with
metrics, which allows investors and fund managers to make data-driven
decisions proactively.
