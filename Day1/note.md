
# Day1 - Mini DS Bootcamp2024

DataRockie Basecamp


## sort spreedsheet เบื้องต้น

ตารางเริ่มต้น

<img width="617" alt="Screenshot 2567-04-24 at 14 06 40" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/c52e1261-70ae-4a89-bc47-7fc86fb7433a">  
<br/><br/>
<br/><br/>
 การกำหนดชื่อให้ตาราง
<br/><br/>
<img width="785" alt="Screenshot 2567-04-24 at 14 08 30" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/2d8278d7-935a-4e89-ad97-3fa90e27774e">

<br/><br/>
<br/><br/> 
ดึงทุกคอลัมที่อยู่ใน sale table
```bash
  =QUERY(SaleData,"SELECT * ")
```
<img width="617" alt="Screenshot 2567-04-25 at 13 45 06" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/f57b13ba-b9e1-4001-b10d-05f056373c16">
<br/><br/>
<br/><br/>

ดึงคอลัม A,B,Cที่อยู่ใน sale table  
```bash
  =QUERY(SaleData,"Select A,B,C")
```
<img width="393" alt="Screenshot 2567-04-25 at 13 46 25" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/d022db0f-969d-45f1-80f8-6df404d7ac98">
<br/><br/>
<br/><br/>


ดึงคอลัม A,B,Cที่อยู่ใน sale table / C  = apple pie
```bash
=QUERY(SaleData,"Select A,B,C WHERE C = 'Apple Pie'")
```
<img width="385" alt="Screenshot 2567-04-25 at 13 47 16" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/463e088b-9588-4e5b-953a-ec0c22b8b418">
<br/><br/>
<br/><br/>

ดึงทุก column ที่อยู่ใน sale table / อาหารถูกกว่า 10 เหรียญ 
/ C  = apple pie
```bash
=QUERY(SaleData,"SELECT * WHERE E < 10")
```
<img width="618" alt="Screenshot 2567-04-25 at 13 48 25" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/0b034a81-7bda-4bf3-9ad1-dc72f3a871d5">

<br/><br/>
<br/><br/>

## SQL and Prompt Engineering 101

What did you learn while building this project? 


### Google gemini

Use google gemini to help teach writing 
sql commands.

### Prompt :
```bash
You are an SQL expert, with 20 years of experience in database.

Please teach me how to write SQL queries to analyze data using SQLite syntax. My goal is to learn SQL and become a junior data analyst.Please concept using simple language for beginners.

Let's write our first query. I want to select all columns from a "customer" table.
```

### Output :
<img width="638" alt="Screenshot 2567-04-25 at 14 42 54" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/f558bafa-4112-44f6-a424-2326aee42282">
<br/><br/>
<br/><br/>

### Prompt :
```bash
I want to select columns “first name” , “last name “, “country”, “address” from a “customer” table.
```
### Output :
<img width="551" alt="Screenshot 2567-04-24 at 15 04 38" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/3e3ca2ed-fe7c-4024-89de-0d555c215a2e">

<br/><br/>
<br/><br/>

### Prompt :
```bash
I want to modify below query in backticks to add another condition to filter only customers with gmail.com

'''
SELECT firstname, lastname, country, email, address FROM customer
WHERE country = "USA' OR country = "Japan'
'''
```
### Output :
<img width="683" alt="Screenshot 2567-04-24 at 16 38 58" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/46b487c0-3b83-4bfc-91e1-23c504cd3541">

<br/><br/>
<br/><br/>


### Prompt :
```bash
thx for your response. I want to add one more column 'salary to a select clause. And then sort the result by salary from high to low.

Please write this Query
```
### Output :
<img width="672" alt="Screenshot 2567-04-24 at 16 42 17" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/27a4be75-80ed-4012-937b-f0eba437452a">
<br/><br/>
<br/><br/>
