# Progetto di Linguistica Computazionale: Analisi del Genere e Sentiment su Twitter

## Descrizione del Progetto
Questo progetto analizza un corpus di tweet in lingua inglese riguardanti tematiche di genere, con particolare attenzione alle persone non-binarie o in fase di transizione.  
L'obiettivo principale è duplice:

1. **Analisi Linguistica**: Verificare l'uso dei pronomi (neutri vs di genere) per comprendere come gli utenti si interfacciano con le identità non binarie.  
2. **Analisi del Sentiment**: Determinare la connotazione emotiva generale (positiva o negativa) dei tweet raccolti utilizzando tecniche di embedding e similarità vettoriale.

---

## Metodologia e Workflow

### 1. Pre-processing dei Dati
Il dataset è stato pulito e normalizzato tramite:
- Rimozione di punteggiatura, URL e caratteri speciali.
- Tokenizzazione e lemmatizzazione del testo.
- Gestione dei dati tramite la libreria `pandas`.

### 2. Analisi dei Pronomi
- Estrazione mirata dei pronomi per osservare la prevalenza di forme neutre (es. they/them).  
- **Risultato:** Prevalenza di pronomi neutri, suggerendo un tentativo di astensione dal genere marcato nel discorso pubblico analizzato.

### 3. Sentiment Analysis (Cosine Similarity)
- **Embeddings:** Conversione dei tweet in vettori numerici tramite `SentenceTransformer`.  
- **Lessico Etichettato:** Caricamento di un dataset di parole con connotazione positiva e negativa nota.  
- **Calcolo della Similarità:** Utilizzo della cosine similarity tra i vettori dei tweet e quelli del lessico per determinare il sentiment.

---

## Strumenti e Tecnologie Utilizzate
- **Linguaggio:** Python 3.11  
- **Ambiente:** Jupyter Notebook / Kaggle  

**Librerie principali:**
- `numpy` e `pandas` – manipolazione dati  
- `SentenceTransformer` – generazione di embeddings testuali  
- `scikit-learn` – calcolo della cosine similarity  
- `matplotlib` e `seaborn` – visualizzazione dati e grafici  

---

## Risultati Principali
- **Distribuzione Linguistica:** La maggior parte dei pronomi rilevati è di natura neutra.  
- **Sentiment Generale:** I tweet analizzati presentano una connotazione tendenzialmente negativa, evidenziando un clima di dibattito teso o critico attorno alle tematiche trattate.


ati presentano una connotazione tendenzialmente negativa, evidenziando un clima di dibattito teso o critico attorno alle tematiche trattate.
