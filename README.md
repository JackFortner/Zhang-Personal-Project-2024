I started my project with the Fama French Model. From their I added a factor for liquidity and profitability/efficiency. For the liquidity factor, I created a portfolio of 15 stocks with
the highest trading volumes from the S&P 500. Since I looked at returns since 2015, I only selected stocks that maintained a high trading volume during that period.
Next, I created an illiquid portfolio of 15 stocks with the lowest consistent trading volumes in the SP500. I took the weighted average return from both portfolios since 2015
and created my liquidity factor. I found that the liquid portfolio outperformed the illiquid portfolio. It is worth mentioning I adjusted the value weighted return of the illiquid
portfolio based on a ratio of the liquid and illiquid market values. I took a similar approach for the profitability factor but I used ROE as my basis. The "profitable"
portfolio consisted of 15 stocks with the highest and most consistent ROEs over the test period.
