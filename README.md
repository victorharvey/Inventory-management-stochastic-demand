## Inventory Management (Stochastic Demand) 📈

The best replenishment policy for 29,000 SKUs

The larger the number of SKUs you deal with as an inventory manager the more you want a periodic review policy.

It will:
 - Limit the time windows of replenishments.
 - Reduce the number of replenishments.

Inventory management systems take a fixed, rule-based approach to forecasting and replenishment.

The objective is to have a replenishment policy that minimizes ordering, holding and shortage costs.

In the simulation code shared below I run an analysis on how many replenishments it would take per X SKUs per 365 days of sales.

In a continuous review policy 1 SKU can have up to 18 replenishment orders in the first 100 days.

10 SKUs will have 54 replenishment orders in the first 100 days.

100 SKUs will have 935 replenishment order in the first 100 days.

2,294 SKUS will have 19,267 replenishment orders in the first 100 days.

As you can see the growth is exponential and not ideal in a real business setting.

The alternative is to have a periodic review policy set at a certain service level.

The question becomes “what is the service level?”

That is business dependent and requires strategy that is:
 - Fixed on a target in the horizon.
 - Calculates safety stock based on the distribution of demand.
 - Calculates and fixes a reorder point.

It is a strategy decision that needs to consider the possibility of shocks such as stockouts.

## About me
Supply Chain Professional with international experience and a passion for data science. 
Connect with me on LinkedIn: Profile [Profile](https://www.linkedin.com/in/victorkharvey/) 

