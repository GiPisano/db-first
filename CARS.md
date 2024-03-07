# Primo DB
nome repo: db-first

Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.





| FIELD | TYPE | ATTRIBUTES | INDEXES |
|---|---|---|---|
| id | INT | NOT NULL, UNSIGNED, AUTO INCREMENT | PRIMARY KEY  |   
| Brand | VARCHAR(80) | NOT NULL  |   |    
| Model | VARCHAR(80) | NOT NULL  |   |   
| Mileage | FLOAT(8, 2) | NOT NULL  |   | 
| Available | BOOLEAN  | NOT NULL  |   | 
| ProductionYear | DATE | NOT NULL  |   | 
| Color | VARCHAR(30) | NOT NULL  |   | 
| FuelType | VARCHAR(30) | NOT NULL  |   | 
| Description | TEXT | NULL, DEFAULT('Auto')  |   |