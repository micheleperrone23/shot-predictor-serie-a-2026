
# ⚽📊 Serie A Shot Predictor 2025/26

Uno strumento interattivo in Python progettato per l'analisi e la previsione del numero di tiri effettuati dai calciatori di Serie A.

Caratteristiche Principali:
Massima Portabilità e Immediatezza: Il database, che include tutti( 580 giocatori) di serie a , è integrato direttamente nel codice tramite strutture string-buffer.
Questo elimina la dipendenza da file esterni (come i CSV) e assicura l'esecuzione istantanea del tool su qualsiasi piattaforma (come Google Colab o Jupyter).

Pipeline di Data Science Avanzata:
Gestione Dati Internazionali: Implementazione di un algoritmo di normalizzazione Unicode per gestire in modo efficace accenti e caratteri speciali nei nomi dei calciatori stranieri.
Indice di Difficoltà Difensiva: Utilizzo di un sistema di pesatura che sfrutta le statistiche "Against" delle squadre avversarie per contestualizzare e quantificare la difficoltà della partita.
Modellazione Probabilistica: Applicazione della Distribuzione di Poisson per il calcolo delle probabilità relative a eventi discreti (il numero di tiri).
Fattori Ambientali Dinamici: Integrazione del vantaggio (o svantaggio) dato dal fattore campo (Home/Away).


🛠️ Modalità d'Uso
Il notebook fornisce un'interfaccia utente intuitiva: è sufficiente inserire il nome del giocatore e della squadra avversaria.
Il sistema elabora i dati e produce un report completo, che include un'analisi testuale dettagliata e un grafico a barre che visualizza le probabilità di effettuare 1+, 2+, o 3+ tiri in porta.


