<!-- Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

#database concessionario auto

Table Name: cars

Table Columns:

- id - BIGINT | PK | AUTO_INCREMENT | NOTNULL | UNIQUE
- price - FLOAT(7,2) | NOTNULL
- model - VARCHAR(200) | NOTNULL
- first_matriculation - DATE | NULL
- fuel - VARCHAR(25) | NULL
- color - VARCHAR(25) | NULL
- number_plate - VARCHAR(10) | NULL
- original_country - VARCHAR(30) | NULL
- number_of_seats - TINYINT | NULL
- displacement - SMALL | NULL
- transmission - VARCHAR(20) | NULL
- power - VARCHAR(10) | NULL
- number_km - MEDIUMINT | NULL


