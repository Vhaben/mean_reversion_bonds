# Yield Curve Strategies & Mean Reversion 

> CapitOx Quantitative Strategies Fund Project

## About

As a quantitative analyst for CapitOx &mdash; Oxford's premier finance and consulting society &mdash;, I gave a presentation with another analyst on mean reversion applied to yield curve trading strategies.

## Motivation

I was particularly interested in this topic because I had previously explored mean reversion in the [weather derivatives project](https://github.com/Vhaben/weather_options) and was beginning to read about government bonds at the time.

### Objective

The original objective was to develop a systematic trading strategy to capitalise on yield spread movements between government bonds of different maturities across multiple countries.  
Due to time constraints and limited access to data, the project ultimately focused on only one country, Brazil.

## Principles

The principle of the trading strategy that was being tested was a pairs trade between a longer and shorter-term maturity bond.  
Mean reversion entered the picture because the success of the strategy was maximised by identifying the most mean-reverting bonds.  
The code then determined the optimal ratio of the bonds to be long and short, assuming an Ornstein–Uhlenbeck process. It also determined which positions to take, as in a standard pairs trade.

## Process

We divided the work as follows:
- Data sourcing: finding yield curve data, including coupon rates, maturity dates, payouts, etc.
- Coding: data cleaning, researching methods used, and implementation
- Presentation and viability: creating the PowerPoint presentation

I was responsible for coding so I can only speak in detail to that facet.  
The work mostly involved studying the relevant literature, and implementing the methods presented in Python.

One textbook in particular, *Optimal Mean Reversion Trading: Mathematical Analysis And Practical Applications* by Tim Siu-tang Leung, Xin Li (the first in the ['References' section](#references)), was of tremendous help. 

## References

A non-exhaustive list of helpful resources:
- Leung, T. S. T., & Li, X. (2015). Optimal mean reversion trading: Mathematical analysis and practical applications (Vol. 1). World Scientific.
- Rampertshammer, S. (2007). An Ornstein-Uhlenbeck framework for pairs trading. Preprint.
- Holý, V., & Tomanová, P. (2022). Estimation of Ornstein-Uhlenbeck process using ultra-high-frequency data with application to intraday pairs trading strategy. arXiv preprint arXiv:1811.09312.

## License

All files associated with this porject formed part of the CapitOx Quantitative Strategies Academy. All content presented in these files is intended for informational and educational purposes for the fund only and should not be considered as investment advice. The content has been assembled through publicly available information. No responsibility is assumed for the accuracy of the information used within this document and do not assume any liability for it.
