# Portfolio_TOI_DC
## Autori del progetto
Salvatore Vigano' (0757472), studente presso l'Università degli studi di Palermo in Ingegneria Informatica LM (Cybersecurity)
Pietro Calamusa (0765717), studente presso l'Università degli studi di Palermo in Ingegneria Informatica LM (Cybersecurity)

### Descrizione del Progetto
Questo repository contiene un insieme di algoritmi e implementazioni Python utilizzati per affrontare vari problemi di compressione dati, trasformazioni di stringhe e rappresentazioni formali.

### Algoritmi Implementati

#### 1. Generazione di Codici Binari
- **Funzione**: `gen_codici(prefissi, lunghezza)`
- **Descrizione**: Genera tutte le combinazioni di codici binari con prefissi dati e lunghezza specifica.
- **Scopo**: Analisi delle combinazioni possibili per problemi di codifica e compressione.

#### 2. Codifica Huffman
- **Funzione**: Algoritmo completo per generare alberi di codifica ottimale.
- **Descrizione**: Utilizzato per comprimere una stringa minimizzando la lunghezza totale della rappresentazione binaria.
- **Input**: Una stringa da codificare.
- **Output**: Tabella di codifica Huffman e stringa compressa.

#### 3. Distanza di Levenshtein
- **Funzione**: `levenshtein(n)`
- **Descrizione**: Calcola la distanza di Levenshtein tra stringhe binarie.
- **Scopo**: Misura della similarità tra stringhe, utile in compressione e linguistica computazionale.

#### 4. Codifica LZSS
- **Funzione**: `lzss_codifica(stringa, finestra, lunghezza_massima)`
- **Descrizione**: Implementa il metodo LZSS, una variante della compressione basata su dizionari.
- **Input**: Stringa da comprimere, dimensione della finestra e buffer.
- **Output**: Stringa compressa.

#### 5. Trasformazione di Burrows-Wheeler (BWT)
- **Funzione**: `calcola_numero_run(stringa)`
- **Descrizione**: Effettua la trasformazione BWT su una stringa e calcola i "run".
- **Scopo**: Preparazione di dati per ulteriori algoritmi di compressione.

#### 6. Conversione in Forma Normale di Chomsky
- **Funzione**: `conversione_in_chomsky(grammatica)`
- **Descrizione**: Trasforma una grammatica context-free nella forma normale di Chomsky.
- **Scopo**: Rappresentazione compatta e analisi dei linguaggi formali.

### Esecuzione
- Prerequisiti: Python 3.8 o superiore.
- Librerie richieste: `math`, `collections`
