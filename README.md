# ESG_Analysis
This analysis studies the performance of portfolios constructed by selecting securities in the S&P 500 universe based on ESG scores sourced from Yahoo Finance. The stocks in the portfolios are equally weighted and performance are compared with an equally weighted benchmark of all the securities in the S&P 500 universe.

### Observations:
- From this histograms, companies in Real Estate have rather low social, environment and goverance score.
- Most companies have rather low environment score. This is especially true of companies in Health Care, Industrial and Financials. This could be a case that these companies are operating without much environmental concerns to address in the first place.
- Note that companies in Materials and Energy have high environment scores. These companies are likely to focus on addressing this concerns due to their nature of work.
- All companies have some form of governance and hence there are no zero governance score. However, many companies have low governance scores. Possible that companies pay more attention to social and environment concerns that are more obvious to outsiders. Governance scoring requires more information from insiders like staffs and suppliers.
- It is rather obvious that Financial, Energy, Health Care sectors have highest governance, environment and social scores generating average annualised returns. Similar observations can be found for annualised volatility, especially Financials and Health Care.

### Results:
- socialScore portfolio outperformed the benchmark. This portfolio has the highest sharpe ratio at 1.07
- environmentScore, governanceScore and totalEsg portfolios' performances are poor. environmentScore at the bottom with a sharp ratio of only 0.39.
- blinding selecting securities based on good totalEsg underperforms the benchmark significantly.
- good social Score securities come from good performing sectors (Health Care, Industrial, Financials) that outperforms the benchmark.

### Correlation Plots between Sectors and ESG Scores:
![output](https://github.com/user-attachments/assets/b1223619-602b-44dd-94a3-5e48366ca409)

### Cumulative Performance based on ESG Scores:
![image](https://github.com/user-attachments/assets/a730154e-ab6c-4699-8d20-32d47ed6aa98)
