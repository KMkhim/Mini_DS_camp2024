
# Descriptive Stats

- Measures of Central Tendency
    - Mean, Median, Mode
 
<br/>

- Measures of Spread/ Variability
    - SD, Variance

<br/>

- Measures of Position
    - Min, Max, Percentile
<br/>

### Sample Table

<img width="350" alt="Screenshot 2567-04-25 at 21 49 45" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/29384cc9-e23f-4464-86a0-e6181a85378e">
<br/><br/>

## Measures of Central Tendency


#### MEAN :
<img width="300" alt="Screenshot 2567-04-25 at 21 41 59" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/b26cac6e-5c39-431c-a48a-bee95192958f">

<br/><br/>

```bash
=AVERAGE(E2:E17)
```
<img width="250" alt="Screenshot 2567-04-25 at 21 54 27" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/47f88d02-3a5d-49ac-bc8c-1aa546462ce0">

<br/><br/>

#### MEDIAN :

<img width="300" alt="Screenshot 2567-04-25 at 22 01 12" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/e0890773-32c3-4ffc-bd64-73d911921ca3">
<br/><br/><br/>

```bash
=MEDIAN(E2:E17)
```
<img width="250" alt="Screenshot 2567-04-25 at 22 03 56" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/410710f9-692d-463d-a6c8-a7ec2cdc35da">
<br/><br/><br/>

#### MODE :

<img width="300" alt="Screenshot 2567-04-25 at 22 09 00" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/eddee610-c1f3-4d6f-8aa1-98bb76831ec0">
<br/><br/>

```bash 
=MODE(E2:E17)
```
<img width="250" alt="Screenshot 2567-04-25 at 22 11 37" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/df6fcf06-91d3-4874-ad28-db7ddf2313a2">
<br/><br/><br/>

### การแจกแจงปกติ VS การแจกแจงปกติมาตรฐาน

#### การแจกแจงปกติ

<img width="300" alt="Screenshot 2567-04-25 at 22 13 46" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/d03c6893-e1c2-4836-afaf-3d9df218784b">

#### การแจกแจงปกติมาตรฐาน

<img width="300" alt="Screenshot 2567-04-25 at 22 13 59" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/b8accdc8-b6c0-4da9-8588-2bfea5a5dca6">
<br/><br/>

```bash
Mean = Median = Mode
```
<br/><br/><br/>


### กราฟเบ้ซ้าย VS กราฟเบ้ขวา
<br/>

<img width="300" alt="Screenshot 2567-04-25 at 22 17 29" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/4ea36b1d-4f4f-4d01-b5c6-4e7aa357f121">

<br/><br/><br/>

## Measures of Spread/ Variability

### Range (พิสัย)
```bash
max - min
```
<br/><br/><br/>

### Standard deviation (SD) ส่วนเบี่ยงเบนมาตรฐาน

#### ประชากร
<img width="300" alt="Screenshot 2567-04-25 at 22 27 43" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/91ed37b1-b16f-4475-a2f2-d71d13718e55">
<img width="200" alt="Screenshot 2567-04-25 at 22 27 55" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/391af88e-0af6-4496-b30a-dd5ac93babad">
<br/><br/>

#### กลุ่มตัวอย่าง

<img width="300" alt="Screenshot 2567-04-25 at 22 29 35" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/cb563c8a-a0b0-4841-9115-3a1eeac0cfbd">
<img width="200" alt="Screenshot 2567-04-25 at 22 29 39" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/ef1427ab-653e-4e2b-9d27-ee7683703161">
<br/><br/><br/>

```bash
=STDEV.S(E2:E17)
```
<br/>
<img width="250" alt="Screenshot 2567-04-25 at 22 33 32" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/35572592-646e-4fd3-82e0-62adba6adf0d">

<br/><br/><br/>

### Variance (ความแปรปรวน)

<br/>

<img width="300" alt="Screenshot 2567-04-25 at 22 21 34" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/0011eb67-1563-42ce-b11a-c3f4d001c0ae">

- กราฟซ้าย ความแปรปรวนต่ำ  การกระจายต่ำ กราฟสูง

- กราฟขวา ความแปรปรวนสูง การกระจายสูง กราฟต่ำ

<br/>

```bash
=VAR.S(E2:E17)
```
<img width="300" alt="Screenshot 2567-04-25 at 22 35 48" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/d538bc00-28b5-41fd-858e-6c9f9e28262b">
<br/><br/><br/>

## Measures of Position

### MAX

<br/>

```bash
=MAX(E2:E17)
```

<img width="250" alt="Screenshot 2567-04-25 at 22 38 51" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/17be5516-2f9a-4b84-b351-7e2ae45fee3a">

<br/><br/>

### MIN

<br/>

```bash
=MIN(E2:E17)
```

<img width="250" alt="Screenshot 2567-04-25 at 22 40 49" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/921ab53a-2cf9-4e7a-bc3b-4371dce34f53">
<br/><br/>

### Percentile

- Percentile r = 75 คืออยู่ตำแหน่งมากกว่าคนอื่น 75%

<br/>

<img width="300" alt="Screenshot 2567-04-25 at 22 42 46" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/baead8cf-57e3-4cd5-a13f-4c9cd4ed25c8">

<br/>
<br/>

- P25 = Q1
- P50 = Q2
- P75 = Q3

```bash
=PERCENTILE(E2:E17,0.25)
=PERCENTILE(E2:E17,0.50)
=PERCENTILE(E2:E17,0.75)
=QUARTILE(E2:E17,1)
=QUARTILE(E2:E17,2)
=QUARTILE(E2:E17,3)
```

<br/>

<img width="222" alt="Screenshot 2567-04-25 at 22 55 06" src="https://github.com/KMkhim/Mini_DS_camp2024/assets/152082969/f9babc21-0af4-4f66-988b-5a8c85ce81c9">
