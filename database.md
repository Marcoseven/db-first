## Titolo esercizio: Brum brum

## Traccia esercizio:
# Modellizzare la struttura di una tabella per memorizzare tutti i dati riguardanti delle auto usate messe in vendita da un concessionario.
# Come fatto stamattina in classe potete fare un file di testo e scrivre la struttura li.

## Caratteristiche auto usate in vendita:

- id | BIGINT - PRIMARY KEY - AUTO INCREMENT - UNIQUE - NOTNULL
- prezzo | DECIMAL(8,2) - NOTNULL
- sconto | TINYINT - DEFAULT(0) - NULL
- marca | VARCHAR (30) - NOTNULL
- modello | VARCHAR (30) - NOTNULL
- targa-del-veicolo | VARCHAR(20) - UNIQUE - NOTNULL
- numero-sportelli | TINYINT - NULL
- anno-di-produzione | YEAR - NOTNULL
- anno-di-prima-immatricolazione | YEAR - NULL 
- anno-di-rottamazione | YEAR - NULL
- numero-di-km-percorsi | MEDIUMINT - NOTNULL
- tipo-di-alimentazione | VARCHAR(20) - NULL
- consumi | VARCHAR(20) - NULL
- potenza-netta-massima-(kw) | SMALL - NULL 
- unità-di-potenza-del-propulsore-(cv) | SMALL - NULL 
- cubatura-di-un-motore-(cilindrata) | SMALL - NULL
- disponibilità | TINYINT - DEFAULT(1) - NOTNULL
- condizione-generale | TEXT - NULL
- note | TEXT - NULL
