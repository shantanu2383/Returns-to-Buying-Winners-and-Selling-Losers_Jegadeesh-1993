# Jegadeesh_Titman-1993

This code in this repository presents the results of an investigation into the profitability of relative strength trading strategies, based on the methodology outlined in Jegadeesh and Titman's 1993 paper, 'Returns to buying winners and losers'. Our study replicates Table 1 from the original paper, analyzing NYSE and AMEX stocks from 1992 to 2022 using 16 trading strategies that select stocks based on their past returns, with holding periods ranging from 1 to 4 quarters.

To improve the statistical power of our analysis, we adopt the authors' approach of constructing J-month/K-month strategies. Specifically, we select securities based on their returns over the past J months, form ten decile portfolios, and hold the winner portfolio and sell the loser portfolio for K months. To ensure overlapping holding periods, we select portfolios from the current month and the previous K-1 months. This enables us to revise the weights of securities in the entire portfolio in any given month while carrying over the rest from the previous month.

Our findings over the period 1992-2022 are broadly similar to the results reported in Jegadeesh and Titman's Table 1 over the period 1965-1989. Specifically, the zero-cost portfolios generated positive returns, with many of the individual t-statistics being significant even after accounting for the number of tests conducted.

We find that the most successful zero cost strategy selects stocks based on their returns over the previous 9 months and holds the portfolio for 3 months. However in general, the returns across the buy and sell portfolios are consistent and broadly similar, regardless of the holding or formation period.
