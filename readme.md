### Instruction

Modellare la struttura di una tabella per memorizzare tutti i dati riguardanti delle `auto usate` messe in vendita da un concessionario.

DB_NAME: libriary

Table name: car_used

-   ID | INDEX | INT or BIGINT
-   brand | VARCHAR(30) |
-   typology| VARCHAR(20)| NOTNULL | DEFAULT('i don't have info)
-   name | VARCHAR(20) | NOT NULL |
-   alimentation | VARCHAR(15) | NULL
-   image | VARCHAR(255)| NULL
-   power(cavalli) | INT | NULL
-   new-drivers | TINYINT | NULL
-   year | YEAR | NULL|
-   Km | MEDIUMINT | NOTNULL
-   veicol history |VARCHAR(255)|NULL
-   state | VARCHAR(20) | NULL | DEFAULT ('contact the store')
-   price | MEDIUMINT | NOT NULL| DEFAULT ('contact the store')
-   description | TEXT | NULL | DEFAULT('i DON'T HAVE INFO)

| ID | brand | typology | name | km | year | new drvers | veicol history | state | price | description | alimentaztion |
| 1 | Opel | Utility | corsa | 108000 | 2016 | 1 | 15/07/2016 Fabio rossi | solo qualche graffio | 5000 | la vendo per prendermi un suv | benzina |
| ---------- | ------------- | --------------- | ---------- | ------------ | ---------- | ----------- | ------------------------- | ---------------------- | -------- | ------------------------------- | ---------------- |
| 2 | volkswagen | suv | T-cross | 52000 | 2020 | 0 | 30/05/2020 Marco Giunti | come nuova | 2000 | la vendo per prendermi un bmw | diesel |
| ---------- | ------------- | --------------- | ---------- | ------------ | ---------- | ----------- | ------------------------- | ---------------------- | -------- | ------------------------------- | ---------------- |
| 3 | lamborgini | corsa | Revuelto | 10000 | 2023 | 0 | 15/10/2023 Gino Cuneo | come nuova | 350000 | la vendo perche va forte | ibryd |
| ---------- | ------------- | --------------- | ---------- | ------------ | --------- | ----------- | ------------------------- | ---------------------- | -------- | ------------------------------- | --------------- |
