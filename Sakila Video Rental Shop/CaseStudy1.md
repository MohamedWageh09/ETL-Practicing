# Requirement
In this report, we need to extract the revenue earned each month, based on total rent orders each month and rent values.

In the final report we need the following information:

Month Number
Total Amount for this month 

# Applied Logic:
````sql
SELECT MONTH(payment_date) as month, sum(amount) as revenue
from payment
group by MONTH(payment_date)
order by revenue desc;
````

## Package Creation:
<img width="960" alt="image" src="https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/af392f58-5020-47a5-948a-30e96800be76">

## Running Package:
<img width="960" alt="image" src="https://github.com/MohamedWageh09/ETL-Practicing/assets/120044385/ad66f05f-9683-47da-8f52-8246cf02c850">




