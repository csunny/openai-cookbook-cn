# 代码编写示例

GPT-3 能够编写代码与文本

这里是一个示例使用*code-davinci-002* 模型写SQL查询的例子

```
SQL tables (and columns):
* Customers(customer_id, signup_date)
* Streaming(customer_id, video_id, watch_date, watch_minutes)

A well-written SQL query that lists customers who signed up during Match 2020 and watched more than 50 hours of video in their first 30 days:
```
Output
```
SELECT c.customer_id 
FROM Customers c
JOIN Streaming s ON c.customer_id = s.customer_id
WHERE c.signup_date >= '2020-03-01' AND c.signup_date < '2020-04-01'
AND s.watch_date <= c.signup_date + INTERVAL 30 DAY
GROUP BY c.customer_id
HAVING SUM(s.watch_minutes) > 3000;
