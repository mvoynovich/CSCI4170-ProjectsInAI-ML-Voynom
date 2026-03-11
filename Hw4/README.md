Dataset: https://www.kaggle.com/datasets/nicholasjhana/energy-consumption-generation-prices-and-weather?resource=download

The problem:

We want to accurately predict the price of energy in EUR/MWh using past hourly data. This is important as energy markets function similarly to financial markets and energy price prediction helps with transitioning to a renewable based electrical infrastructure.

Sequential models are needed for this problem as unlike regular models the assumption is not that data points or features are independent. This means we can capture the relationship of these points of features as time passes which is extremely important for the energy market as the suppy and demand depends on how much was generated in the past hours.