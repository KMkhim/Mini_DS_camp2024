
# SQL(II)
This project is used by the following companies:

Aggregrate
- COUNT
- AVG
- SUM
- MIN
- MAX

GROUP ... BY

Work with more than one table

-INNER JOIN
<bsp> </bsp>
## Aggregrate

```bash
SELECT 
	COUNT(total)
    ,SUM(total)
    ,MIN(total)
    ,MAX(total)
    ,AVG(total)
FROM invoices
```

<img width="596" alt="Screenshot 2567-04-25 at 16 39 54" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/c01f3cd4-efa2-48f3-ba6f-757f3235e433">

### GROUP .. BY

#### Prompt:
```bash
SELECT 
	STRFTIME ('%Y' , invoicedate ) AS 'year',
	SUM (total),
    AVG (total) 
FROM invoices
GROUP By 1
```
สกัดเฉพาะปี จากคอลัม invoicedate เป็น คอลัม year
หา ผลรวม และ ค่าเฉลี่ย  จับกลุ่มเรียงตามปี

#### Output : 

<img width="832" alt="Screenshot 2567-04-25 at 17 24 40" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/97bbcd23-9594-46ec-bb81-57e668878546">

### INNER JOIN

#### Prompt :
```bash 
SELECT c.firstname, c.lastname, c.Country , i.InvoiceId 
FROM customers c
INNER JOIN invoices i ON c.CustomerId = i.InvoiceId
WHERE country = 'USA' OR country = 'Japan'
```
#### Output :

<img width="847" alt="Screenshot 2567-04-25 at 18 04 03" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/375584c8-2c21-4beb-93f1-e283b50f44bd">


### CASE

#### Prompt :
```bash
SELECT customerid , SUM(total),
	CASE WHEN sum(total) >= 40 THEN 'high'
    ELSE 'low' END AS 'segment'
FROM invoices
GROUP BY customerid
ORDER BY segment DESC;
```

#### Output :

<img width="901" alt="Screenshot 2567-04-25 at 18 37 46" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/96841660-3e5b-434f-9c9d-f71ce2f8eb4a">

DESC: This keyword indicates descending order, sorting from highest to lowest salary.


