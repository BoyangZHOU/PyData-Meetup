# Equity Option Implied Volatility Analytics with Python

Notebook for 19 January PyData Singapore Meetup

Python has become an increasingly important tool in the domain of quantitative and algorithmic trading and research. This extends from senior quantitative analysts pricing complex derivatives using numerical techniques all the way to the retail trader using closed form valuation methods and analysis techniques. This talk will focus on the uses of Python in discovering unobserved features of listed equity options.

The Black-Scholes option pricing formula was first published in 1973 in a paper called "The Pricing of Options and Corporate Liabilities". In that paper Fischer Black and Myron Scholes derived an equation which estimates the price of an option over time. This formula and its associated "greeks" have become ubiquitous in options trading.

In this talk, we'll demonstrate how to gather options data using the Pandas module and apply various transformations to obtain the theoretical value of the option and the associated greeks. We'll then extend the talk to discuss implied volatility and show how to use Numpy methods to compute implied volatility. We'll use the results to visualize the so-called volatility skew and term structure to help inform potential trading decisions.