# Monte-Carlo-Simulation-Future-Stock-Prices-for-Apple

Simply put, Monte Carlo simulation is the simulation of future outcomes of an event. In this exercise, I built the Monte Carlo model to simulate the distribution of possible future prices for Apple for 3000 trials. I was able to uncover some interesting statistics from the simulation

Using the 12-year Yahoo Finance API historical stock data set for Apple , I generated future random shocks, based on daily volatilities in returns (observed and simulated). All premised on the assumption of normal distribution and using numpy, I concluded that Apple offers more upside than downward potential. 

# Why I decided to use Python: 
 I believe the simulation would be faster in Python( than Excel) and Python would allow me uncover more robust insights and stats

# Analysis of Results
#In the next year, there would likely be more upside potential for Apple stock than downsides, given the current price
#This derives from the expected/mean price observed for the chosen period, which we put at 173.74 dollars. 
#Corroborating this position, is that there is only 10 per cent chance that the price will fall below USD 115.07
#It is noteworthy that these insights and analyses, are based solely on Monte Carlo Simulation of possible future outcomes

# Disclaimer: 
#As there are many more factors (other than historical per cent changes/ random walk), that drive stock prices, 
#I would be wary of making investment decision/recommendations solely off of Monte Carlo Simulation. 
#That said, this offers a thorough illustration of the Monte Carlo simulation, as I continue to explore methods and techniques 
#..to better understand distribution of possible outcomes of events in different knowledge domains

# Room for Improvement: 
I have collected data set that cover a 12-year historical period for this exercise. I believe it would be tremendously valuable to test sensitivities of different ranges 

#Numpy#Random-walk Process#MonteCarloSimulation#LawofLargeNumbers

Reference Materials:
https://www.palisade.com/risk/monte_carlo_simulation.asp
