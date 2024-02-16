# FLO_CLTV_PREDICTION



![FLO](https://github.com/Merttcoskun/FLO_CLTV_PREDICTION/assets/111244707/2d4928f9-8ae8-4bf8-9d39-dc9b036b397e)


FLO CLTV PREDICTION with BG-NBD ve GAMMA-GAMMA


<h3> Business Problems <h3>

FLO wants to set a roadmap for sales and marketing activities. In order for the company to make a medium-long-term plan, it is necessary to estimate the potential value that existing customers will provide to the company in the future.

<h3> Dataset Story <h3>

The dataset consists of information obtained from the past shopping behaviors of customers who made their last purchases as OmniChannel (both online and offline shopper) in 2020 - 2021.


### Customer Information

- **master_id**: Unique customer ID
- **order_channel**: Channel used for shopping (Android, iOS, Desktop, Mobile)
- **last_order_channel**: Channel used for the last purchase
- **first_order_date**: Date of the first purchase made by the customer
- **last_order_date**: Date of the last purchase made by the customer
- **last_order_date_online**: Date of the last online purchase made by the customer
- **last_order_date_offline**: Date of the last offline purchase made by the customer
- **order_num_total_ever_online**: Total number of purchases made by the customer online
- **order_num_total_ever_offline**: Total number of purchases made by the customer offline
- **customer_value_total_ever_offline**: Total amount spent by the customer in offline purchases
- **customer_value_total_ever_online**: Total amount spent by the customer in online purchases
- **interested_in_categories_12**: List of categories the customer has shopped in the last 12 months
- **store_type**: Represents three different companies. If a customer has shopped from Company A and B, it is written as A,B.
