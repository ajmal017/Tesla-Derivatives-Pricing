# Tesla-Derivatives-Pricing
Crazy to think that the Black Scholes paper was published in 1973 and is still a core model taught by Finance professors accross the world.  

## Methodology
- Used data from yfinance i.e. the option chain .csv file they publish
- Calculated T with numpy and kept it at business days i.e. 252, moreover if T = 0, I changed the figure to 0.000001 in order to get an output
- Calculated the Euro Call price using the Black-Scholes formula with pandas (if there are any errors please let me know)
- Used options that were currenty "in the money"
- Created a free account with Azure ML and was able to run an AutoML regression experiment that tried various different algorithms that predict the price of the option 

## Findings
![alt text](https://user-images.githubusercontent.com/49772033/95673828-e747c480-0bf7-11eb-89a4-f64f98f5ea22.png)

