<!-- 
Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario -->

# Used Car Dealer Database

## Table name

- used car

## Table column

- id | PK, SMALLINT AUTO_INCREMENT, UNIQUE, NOT NULL
- marca | VARCHAR(15), NOT NULL
- modello | VARCHAR(15), NOT NULL
- segmento | VARCHAR(40), NULL
- anno produzione | YEAR, NULL
- anno prima immatricolazione | DATE, NOT NULL
- alimentazione | VARCHAR(40), NULL
- potenza cv/kw | VARCHAR (10), NULL
- chilometraggio | FLOAT(6, 3), NULL // 999,999 KM
- trasmissione | VARCHAR(70), NULL
- prezzo | DECIMAL(6, 3), NULL // 999.999 €
- colore | VARCHAR(20), NULL
- decrizione | VARCHAR(255), NULL
- immagine | VARCHAR(255), NULL
- numero telaio | VARCHAR(20), NULL
- note | VARCHAR(255), NULL

