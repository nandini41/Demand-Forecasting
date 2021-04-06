# Demand-Forecasting
The data consisted of demand of five products for thirty time periods. 
The aim was to apply Exponential Smoothening to predict demand of the products.
## Exponential Smoothnig
This forecating technique is used when demand is very stable. It takes average of all past demand, but weights recent data more heavily, and older data less heavily. 

Forecasted demand at time t is given by the sum of weighted coefficient(α)*demand at previous time period(D(t-1)) and (1-α)*forecasted demand at previous time period(F(t-1)). Mathematically it is represented as F(t)= αD(t-1)+(1-α)F(t-1) where α changes weights and varies how much weight is applied to each period.
The approperiate α is chosen by hit and trial method, checking accuracy measures for each value of α. The one with least error is finalized. 

