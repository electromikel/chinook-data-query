  SELECT lastname, firstname
 FROM employee
 -----
SELECT albumid,title,artistid
FROM album

SELECT * FROM customer


------
SELECT * FROM employee WHERE reportsto  = 2
--------
SELECT * FROM customer WHERE country = 'usa' and state = 'ca'

SELECT * FROM customer WHERE customerid > 2

SELECT * FROM customer WHERE customerid >= 20

SELECT * FROM customer WHERE customerid IN (2,6,8,15,22)


SELECT * FROM customer WHERE customerid BETWEEN 16 and 22

SELECT * FROM customer
WHERE country LIKE 'b%'

  SELECT country, COUNT(country) FROM customer GROUP BY country 

SELECT sum(total) FROM invoice
SELECT * FROM album ORDER BY Title ASC
SELECT * FROM artist WHERE Name like 'b%'

SELECT * FROM customer WHERE city = 'oslo'
SELECT COUNT(*) FROM customer  WHERE country = 'canada'

 SELECT AVG(unitprice) FROM TRACK ORDER BY 'unitprice'

SELECT SUM(total) FROM invoice ORDER BY 'BillingCountry'

SELECT * FROM employee ORDER BY lastname LIKE 'P%' LIMIT 3
SELECT * FROM track
WHERE genreid = 1

SELECT * FROM track
WHERE albumid = 3

SELECT AVG(unitprice)
FROM track
ORDER BY name

SELECT * FROM employee
WHERE city = 'calgary'


SELECT * 
FROM workers
 
