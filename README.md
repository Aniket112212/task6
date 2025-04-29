This line selects and calculates the following:
YEAR(order_date) → extracts the year from each order’s date.
MONTH(order_date) → extracts the month.
SUM(amount) → adds up the total sales (revenue) for each month.
COUNT(DISTINCT order_id) → counts the number of unique orders placed in that month (i.e., order volume).
i'm building a monthly summary of sales activity.
