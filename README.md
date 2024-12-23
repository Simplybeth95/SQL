SELECT*
FROM superstore
ORDER BY price;
SELECT AVG(price)
FROM superstore;
SELECT item_name, price
FROM superstore
WHERE category = 'Kitchen Supplies'
ORDER BY price DESC
LIMIT 1;
SELECT COUNT(item_name)
FROM superstore
WHERE category ='Electronics'
