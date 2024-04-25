
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

