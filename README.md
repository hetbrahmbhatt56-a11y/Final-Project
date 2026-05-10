# Treasury Bond Returns vs. Corporate Bond Returns

In this project I compared the returns of Treasury bonds and investment grade corporate bonds. Treasury bond returns are represented by the iShares 7-10 Year Treasury Bond ETF (IEF), while corporate bond returns are represented by the iShares iBoxx $ Investment Grade Corporate Bond ETF (LQD). The project also uses interest rate data and corporate credit-spread data to help explain how bond returns changed under different market conditions.

# Research Question : How have Treasury bond returns compared with investment grade corporate bond returns, and how are those returns related to changes in interest rates and corporate credit spreads?

## Data Sources

1. **Treasury Bond Return Data**  
   Dataset: iShares 7-10 Year Treasury Bond ETF (IEF)  
   Source: Yahoo Finance  
   Link: https://finance.yahoo.com/quote/IEF/history/  
   Use in project: Used to represent Treasury bond returns.

2. **Corporate Bond Return Data**  
   Dataset: iShares iBoxx $ Investment Grade Corporate Bond ETF (LQD)  
   Source: Yahoo Finance  
   Link: https://finance.yahoo.com/quote/LQD/history/  
   Use in project: Used to represent investment-grade corporate bond returns.

3. **Treasury Interest-Rate Data**  
   Dataset: 10-Year Treasury Constant Maturity Rate (DGS10)  
   Source: FRED, Federal Reserve Bank of St. Louis  
   Link: https://fred.stlouisfed.org/graph/fredgraph.csv?id=DGS10  
   Use in project: Used to measure the interest-rate environment.

4. **Corporate Credit-Spread Data**  
   Dataset: ICE BofA U.S. Corporate Index Option-Adjusted Spread (BAMLC0A0CM)  
   Source: FRED, Federal Reserve Bank of St. Louis  
   Link: https://fred.stlouisfed.org/graph/fredgraph.csv?id=BAMLC0A0CM  
   Use in project: Used to measure credit risk in the corporate bond market.

## Files

- `final_project.Rmd`: Main R Markdown file.
- `final_project.html`: Knitted HTML report.
