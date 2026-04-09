# 🧙🏻​ Grimorio

Il mio Grimorio personale – un diario digitale fantasy per organizzare mappe, appunti, creature, oggetti, sessioni di gioco e tutto il worldbuilding. [Work in Progress]

### ✨ Cos'è Grimorio?

**Grimorio** è un'applicazione web semplice gestire il tuo archivio personale in stile fantasy.  
Puoi creare pagine, categorizzarle, aggiungere mappe e immagini, e tenere tutto sotto controllo.

### 🌐 Link alla pagina

→ **[Apri il mio Grimorio](https://lander-ix.github.io/Grimorio/)**

### 💾 I 3 metodi di salvataggio

**tre diversi modi** per salvare i tuoi dati:

1. **Sul Browser** (locale automatico)  
   I dati vengono salvati automaticamente nel browser usando `localStorage`.  
   **Vantaggio**: comodo e immediato.  
   **Svantaggio**: se cancelli la cache i dati vanno persi.

2. **File JSON sul PC** (esportabile)  
   Puoi scaricare un file `JSON` sul tuo computer. Sarà il tuo archivio/database anche come backup  
   Le modifiche vengono salvate direttamente su quel file (usa la File System Access API).  
   Ideale per avere un backup fisico o per modificare manualmente il file.

3. **Sincronizzazione con GitHub** (cloud personale)  
   Puoi sincronizzare automaticamente il tuo archivio con un repository GitHub.  
   I dati vengono salvati nel file `data.json` (o il nome che preferisci) sul tuo repository. (Tramite un Personal Access Token)
   - Nella sezione github dell'app inserire il proprio Nome Utente di Github, Il nome della repository che avete creato, il Personal Access Token ed infine il nome file [ data.json ]

 ### Note

- È un progetto **statico** → non richiede server o database.
- I dati sono salvati in chiaro nel file JSON (quindi è facile da editare).

### ⚙
