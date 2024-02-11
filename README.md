# End-to-end-Gravity-Books-project

start from creating data warhouse schema then ETL using SSIS


Create data cubes for analyzing orders and customer data.

then using SSIS for systematic data collection, organizing information on books, customers, and sales

Then SSAS for data cubes and analysis of order trends and customer behavior.

-----------------------
## Database source
<img width="661" alt="data source erd" src="https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/ed7c661d-ce5f-4e70-aa4f-109c5815e0bb">

-----------------------
## DWH modeling

Then i build a datawarehous schema, Snowflake schema is suitble due to the normalization of gravitybook store.

![image](https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/54094c2b-91b2-4ed0-8fbc-db86cff4aa2d)

--------------------

## ETL using SSIS
Extract - transform - load data 

### Fact Order Table

<img width="681" alt="fact 1 order" src="https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/40453e77-0b06-4894-ae37-9e63fb9bf780">

### Data in fact table 

<img width="721" alt="fact data" src="https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/de4724a0-cedd-493d-a993-7233e29340cf">

### Dim book
<img width="700" alt="Customer" src="https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/9b882f9b-2655-4ac9-8688-7bfa317a3d1b">

### Data in Dim book
<img width="730" alt="biik" src="https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/14e58439-9a81-49dd-b9bd-0e678249bace">

-------------------------
## Data Cube - SSAS

![SSAS1](https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/f2f624aa-d005-4ebc-b747-3942a9f05a69)


## Dashboard using power BI

<img width="593" alt="book book" src="https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/50bf77fb-6fc4-400a-af6c-374d6786681e">






