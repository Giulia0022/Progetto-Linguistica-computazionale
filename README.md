Progetto di Linguistica Computazionale: Analisi del Genere e Sentiment su Twitter
Descrizione del Progetto
Il presente lavoro analizza un corpus di tweet in lingua inglese riguardanti le tematiche di genere, con particolare attenzione alle persone non-binarie o in fase di transizione. L'obiettivo è duplice:

Analisi Linguistica: Verificare l'uso dei pronomi (neutri vs di genere) per comprendere come gli utenti si interfacciano con le identità non binarie.

Analisi del Sentiment: Determinare la connotazione emotiva generale (positiva o negativa) dei tweet raccolti utilizzando tecniche di embedding e similarità vettoriale.

##Metodologia e Workflow##
1. Pre-processing dei Dati
Il dataset è stato pulito e normalizzato per l'analisi:

Rimozione di punteggiatura, URL e caratteri speciali.

Tokenizzazione e lemmatizzazione del testo.

Gestione dei dati tramite la libreria pandas.

2. Analisi dei Pronomi
È stata condotta un'estrazione mirata dei pronomi per osservare la prevalenza di forme neutre (es. they/them).

Risultato: Emerge una prevalenza di pronomi neutri, facilitata anche dalla struttura della lingua inglese, suggerendo un tentativo di astensione dal genere marcato nel discorso pubblico analizzato.

3. Sentiment Analysis (Cosine Similarity)
A differenza dei metodi classici (classificatori addestrati), questo progetto utilizza un approccio basato sul "metodo del più simile":

Embeddings: Utilizzo della libreria SentenceTransformer per convertire i tweet in vettori numerici.

Lessico Etichettato: Caricamento di un dataset di parole con connotazione positiva e negativa nota.

Calcolo della Similarità: Utilizzo della Cosine Similarity tra i vettori dei tweet e i vettori delle parole del lessico.

Strumenti e Tecnologie Utilizzate
Linguaggio: Python 3.11

Ambiente: Jupyter Notebook / Kaggle

Librerie Principali:

numpy e pandas: Manipolazione dati.

SentenceTransformer: Generazione di embeddings testuali.

scikit-learn: Calcolo della cosine similarity.

matplotlib e seaborn: Visualizzazione dei dati e dei grafici finali.

Risultati Principali
Distribuzione Linguistica: La maggior parte dei pronomi rilevati è di natura neutra.

Sentiment Generale: Dalla comparazione delle medie delle similarità, i tweet analizzati presentano una connotazione tendenzialmente negativa, evidenziando un clima di dibattito teso o critico attorno alle tematiche trattate.
