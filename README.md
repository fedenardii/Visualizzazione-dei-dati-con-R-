
# Visualizzazione dei dati con R — Edvance / UniPi 📊📈
 
Dispensa personale sul corso **Visualizzazione dei dati con R** dell’**Università di Pisa**, tenuto dai **Prof. Vito Giordano, Prof.ssa Irene Spada e Prof. Filippo Chiarello** e disponibile sulla piattaforma **Edvance**.
> 📌 Materiale rielaborato a scopo di studio.
> Non è materiale ufficiale, non è vendibile e non ha finalità commerciali.
---
 
 
## 🚀 Cos’è Edvance
 
**Edvance** è una piattaforma di formazione digitale universitaria che offre corsi online, spesso gratuiti e in formato **MOOC**.
 
```
Edvance
→ corsi online universitari
→ materiali e quiz
→ formazione digitale accessibile
→ Open Badge finali
 
```
 
---
 
 
## 🏅 Open Badge
 
Al termine dei corsi è possibile ottenere un **Open Badge**, cioè un attestato digitale verificabile.
 
È utile perché:
 
- certifica il completamento del corso;
- può essere inserito nel **CV**;
- può essere aggiunto a **LinkedIn**;
- rende più visibili competenze digitali e trasversali.
> ⚠️ Un badge non sostituisce una certificazione professionale avanzata, ma documenta un percorso formativo riconoscibile.
---
 
 
## 📚 Capitoli trattati
 
Il corso è un MOOC suddiviso in **quattro moduli**, che nella dispensa diventano **dieci capitoli**, dai fondamenti della Data Science fino alle regole per comunicare i dati senza distorcerli.
 
### 🔹 Capitolo 1 — Data Science: dal dato alla conoscenza
 
Focus sui concetti di base: cos’è la Data Science e come nasce un’analisi rigorosa.
 
- metodo scientifico applicato ai dati;
- scala dato → informazione → conoscenza;
- tipologie di dati (tabellari, immagini, testi);
- struttura del percorso di studio.
### 🔹 Capitolo 2 — Principi della Data Visualization
 
Focus sui tre pilastri che rendono una visualizzazione efficace.
 
- chiarezza, accuratezza, efficienza;
- data-ink ratio (Tufte);
- elementi da eliminare;
- procedura per costruire una buona visualizzazione.
### 🔹 Capitolo 3 — R e RStudio: l’ambiente di lavoro
 
Focus sugli strumenti: linguaggio, IDE, pacchetti e sintassi di base.
 
- differenza tra R e RStudio;
- installazione e caricamento dei pacchetti;
- interfaccia a quattro pannelli di RStudio;
- sintassi delle funzioni e riproducibilità.
### 🔹 Capitolo 4 — Il Tidyverse: una grammatica per i dati
 
Focus su dplyr e sulla filosofia dei dati tidy.
 
- concetto di dato tidy;
- verbi di dplyr (select, filter, mutate, summarise…);
- operatore pipe `%>%`;
- differenza tra `%>%` e `+`;
- stile del codice.
### 🔹 Capitolo 5 — La grammatica dei grafici con ggplot2
 
Focus sulla struttura di un grafico ggplot2 costruito a livelli.
 
- estetiche, geometrie, scale, coordinate, temi;
- dataset penguins;
- costruzione incrementale del grafico;
- mapping vs setting;
- faceting con `facet_wrap` e `facet_grid`.
### 🔹 Capitolo 6 — Visualizzare variabili numeriche
 
Focus su come descrivere e confrontare distribuzioni numeriche.
 
- istogramma e binwidth;
- grafico di densità;
- box plot per confronto tra gruppi;
- scatterplot e hex plot;
- linea di tendenza con `geom_smooth`.
### 🔹 Capitolo 7 — Visualizzare variabili categoriche
 
Focus sui grafici a barre e sulle relazioni miste numerica × categorica.
 
- barre semplici, segmentate, proporzionali;
- confronto numerica × categorica;
- box plot, violin plot, ridge plot;
- come scegliere in base al tipo di variabile.
### 🔹 Capitolo 8 — Scegliere il grafico giusto
 
Focus sulla scelta del grafico in funzione della finalità comunicativa.
 
- elementi di un grafico e proprietà visive;
- confronto, distribuzione, proporzioni, relazioni;
- quando (non) usare il grafico a torta;
- rappresentare l’incertezza.
### 🔹 Capitolo 9 — Personalizzare i grafici con `theme()` e `labs()`
 
Focus su come rendere un grafico chiaro senza appesantirlo.
 
- funzione `theme()` e temi predefiniti;
- titoli, sottotitoli e didascalie con `labs()`;
- annotazioni con `annotate()`;
- colore, accessibilità e codifica ridondante;
- griglie, sfondo e dimensioni.
### 🔹 Capitolo 10 — Presentare i dati in modo efficace
 
Focus sulle cinque regole per comunicare i dati senza distorcerli.
 
- scegliere il giusto tipo di visualizzazione;
- evitare rappresentazioni e scale fuorvianti;
- meno è meglio (data-ink);
- cancellare entro limiti ragionevoli;
- raccontare una storia senza mentire con i dati;
- correlazione ≠ causalità.
---
 
 
## 🧠 Obiettivo
 
La dispensa non è un riassunto telegrafico.
 
È pensata come supporto di studio, con spiegazioni discorsive, esempi di codice, immagini di output attese e frasi da ricordare.
 
---
 
 
## 🗂️ Struttura
 
| Parte    | Contenuto                                         |
| -------- | ------------------------------------------------- |
| Premessa | Edvance, Open Badge e organizzazione              |
| 1        | Data Science: dal dato alla conoscenza            |
| 2        | Principi della Data Visualization                 |
| 3        | R e RStudio: l’ambiente di lavoro                 |
| 4        | Il Tidyverse: una grammatica per i dati           |
| 5        | La grammatica dei grafici con ggplot2             |
| 6        | Visualizzare variabili numeriche                  |
| 7        | Visualizzare variabili categoriche                |
| 8        | Scegliere il grafico giusto                       |
| 9        | Personalizzare i grafici con `theme()` e `labs()` |
| 10       | Presentare i dati in modo efficace                |
| Mappa    | Mappa finale dal dato al grafico                  |
 
---
 
 
## ✅ Prerequisiti
 
Non servono competenze tecniche avanzate.
 
È utile conoscere:
 
- uso base del computer e dei file CSV;
- nozioni minime di statistica descrittiva (media, mediana);
- cosa si intende per dataset e variabile;
- curiosità verso l’analisi dei dati;
- interesse per la comunicazione visiva delle informazioni.
---
 
 
## ⚠️ Disclaimer
 
Questa dispensa è una **rielaborazione personale** dei materiali del corso Edvance / Università di Pisa.
 
Non sostituisce:
 
- lezioni ufficiali;
- quiz ufficiali;
- materiali della piattaforma;
- indicazioni dei docenti.
Non mi assumo responsabilità per:
 
- errori o imprecisioni;
- aggiornamenti futuri dei corsi;
- uso improprio del materiale;
- interpretazioni scorrette.
------
Il materiale è:
 
```
personale
didattico
non ufficiale
non commerciale
non vendibile
 
```
 
