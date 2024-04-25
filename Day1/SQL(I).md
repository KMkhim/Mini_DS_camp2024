
# SQL
This project is used by the following companies:

- SELECT.....FROM
- WHERE
- ORDER ... BY --sortData
- LIMIT
- 
<br/>

## SELECT.....FROM

```bash
SELECT firstname, lastname, company, country
FROM customers
```
<br/>
เลือกคอลัม "firstname" , "lastname", "company", "country"
จากตาราง "customers"

<br/><br/>
## WHERE
```bash
SELECT firstname, lastname, company, country
FROM customers
WHERE country = 'USA' OR country = 'United Kingdom'
```
<br/>
เพิ่มการ filter "coutry" เอาเฉพาะ "customers" ที่อาศัยใน "USA" หรือ "United Kingdom"
<br/><br/>

## Gemini

#### Prompt:
```bash
Let's start over. I want to query data from customers table

Select these columns. firstname, lastname, company, country, email And filter customers in USA OR United Kingdom
```
<br/>

#### Output : 

<img width="700" alt="Screenshot 2567-04-25 at 15 25 24" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/fa536b76-2d28-40b4-a60c-bcf334c714b7">
<br/><br/>

#### Prompt :
```bash 
Add two conditions to our previous query, filter customers whose age between 18- 29 years old and still have our subscription (column subscription is yes)
```
<br/>

#### Output :

<img width="700" alt="Screenshot 2567-04-25 at 15 25 24" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/29c8d2c2-d152-4871-84e5-33d5103a9ebd">
<br/><br/>

## ORDER ... BY 


#### Prompt :
```bash
Well done!

I want to sort the result set by salary from high to low. Please add salary column to our previous query
```
<br/>

#### Output :

<img width="734" alt="Screenshot 2567-04-25 at 15 28 52" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/171349e1-29a9-4e54-90dd-5cb1b0b5a920">

DESC: This keyword indicates descending order, sorting from highest to lowest salary.
<br/><br/>


## LIMIT

#### Prompt :
```bash
Limit the results to top 100 customers. 
```
<br/>

#### Output :

<img width="716" alt="Screenshot 2567-04-25 at 15 32 44" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/dd244616-b0c3-4c93-8c4e-6f9e49d4ede7">

<br/><br/>

#### Query :

```bash
SELECT firstname, lastname, company, country, email
FROM customers
WHERE country IN ('USA' , 'United Kingdom')
ORDER BY firstname DESC
LIMIT 5
```
<br/>
#### Output :
<img width="901" alt="Screenshot 2567-04-25 at 15 51 16" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/96be1783-db80-40a1-a7af-e5cf0fa466a6">
