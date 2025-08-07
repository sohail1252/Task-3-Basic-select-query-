CREATE TABLE products (
product_id SERIAL PRIMARY KEY,
name VARCHAR(100),
category VARCHAR(50),
price NUMERIC(10, 2),
quantity INTEGER
);

INSERT INTO products (name, category, price, quantity) VALUES
('Apple iPhone', 'Electronics', 900, 10),
('Dell Laptop', 'Electronics', 1200, 5),
('Nike Shoes', 'Footwear', 120, 20),
('Adidas Tee', 'Clothing', 25, 50),
('Sony TV', 'Electronics', 700, 7);

SELECT *
FROM products
WHERE category = 'Electronics'
AND price BETWEEN 700 AND 1200
AND name LIKE 'S%'
ORDER BY price DESC;

SELECT name, price
FROM products
WHERE quantity > 5 OR category = 'Footwear'
ORDER BY name ASC;
