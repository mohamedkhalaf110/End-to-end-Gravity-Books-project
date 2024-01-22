# End-to-end-Gravity-Books-project

start feom creating data warhouse schema then ETL using SSIS

Frist i configured data warhouse schema in sql server ms

then using SSIS for systematic data collection, organizing information on books, customers, and sales
Then SSAS for data cubes and analysis of order trends and customer behavior.

-----------------------
## Database source
<img width="661" alt="data source erd" src="https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/ed7c661d-ce5f-4e70-aa4f-109c5815e0bb">

Then i build a datawarehous schema, Snowflake schema is suitble due to the normalization of gravitybook store.

![DWH](https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/c8f4632b-88b0-4e66-8c63-4a70f96d5cd5)

--------------------

## ETL using SSIS
Extract - transform - load data 

DIM table

![ControlFlow](https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/097f1af6-a489-46a1-908b-e66a3050e3b8)

Fact table

![factTable](https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/86e00941-5ea8-40cb-8e79-c1985a5acb64)

-------------------------
## Data Cube - SSAS

![SSAS1](https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/f2f624aa-d005-4ebc-b747-3942a9f05a69)

![SSAS3](https://github.com/mohamedkhalaf110/End-to-end-Gravity-Books-project/assets/93522514/81c0d2cf-88c1-46ec-b86e-f599b5c08e4d)





