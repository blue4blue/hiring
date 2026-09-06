# SQL Fundamentals

Give the candidate two tables: `users(id, signup_date, country, plan)` and
`orders(id, user_id, amount, status, created_at)`.

* Count users by country.
* Total revenue last month, excluding cancelled orders.
* How many users have never placed an order?
    * Write it two different ways.
* What is the difference between an inner join and a left join here?
    * What happens to the row count in each case?
* Average order value per plan, only for plans with more than 100 orders.
* What is the difference between `COUNT(*)`, `COUNT(user_id)` and `COUNT(DISTINCT user_id)`?
* What does `WHERE status != 'cancelled'` do if some rows have `status` as NULL?
* Find each user's first order date.
* Read this query aloud and tell me what it returns. *(Hand them a 15-line query with a CTE and a join.)*

## Follow-ups to test depth

* "This returns more rows than there are users. Why?"
* "What would you check before trusting this number?"
