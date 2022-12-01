database
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario

Table name: cars

Table Columns:
- id | BIGINT | NOTNULL 
- km | CHAR(13) | NOTNULL
- year | YEAR | NOTNULL
- damage | TEXT | NULL
- status | TEXT | NULL
- model | VARCHAR(200) | NULL
- price | FLOAT | NULL
- license plate | SMALLINT | NULL
- places |  FLOAT(2) | NULL
- extra accessories | TEXT | NULL 