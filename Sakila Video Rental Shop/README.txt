Requirement:
In this report, we need to extract the revenue earned each month, based on total rent orders each month and rent values.

In the final report we need the following information:

Month Number
Total Amount for this month 

The Query:

SELECT MONTH(p.payment_date) as month, sum(p.amount) as revenue
from payment p
group by MONTH(p.payment_date)
order by revenue desc;
