# Ornithopter# 

**OrnithoSim** è una web app interattiva progettata per l'ingegneria e il design di ornitotteri (macchine volanti a battito d'ali). Il simulatore permette di configurare parametri fisici, visualizzare il movimento meccanico in tempo reale e calcolare i requisiti costruttivi necessari per il volo.

---

## Funzionalità Principali

### 1. Simulazione e Visualizzazione
* **Configurazione Parametri:** Modifica in tempo reale le caratteristiche dell'ornitottero (apertura alare, frequenza di battito, inclinazione).
* **Animazione dei Meccanismi:** Visualizza i cinematismi interni (bielle, manovelle e ingranaggi) che trasformano il moto rotatorio del motore nel battito d'ali.

### 2. Calcolo Strutturale e Power System
Inserendo i dati tecnici, l'app calcola automaticamente il setup ideale per la costruzione:
* **Input Utente:** * Peso totale della struttura.
    * Dimensioni (apertura alare e corda).
    * Capacità della batteria (mAh).
    * Autonomia desiderata.
* **Output di Progetto:** Suggerimento del meccanismo di trasmissione e specifiche del motore necessarie per sostenere il volo in base all'autonomia richiesta.

---

## Come Funziona



1.  **Imposta le dimensioni:** Definisci l'estetica e la scala del tuo modello.
2.  **Configura l'elettronica:** Inserisci i dati relativi a batteria e peso per verificare la fattibilità tecnica.
3.  **Simula:** Avvia l'animazione per osservare come il meccanismo risponde ai carichi impostati.
4.  **Esporta:** Ottieni i valori di riferimento per procedere alla costruzione fisica.

---

## Tecnologie Utilizzate

* **Frontend:** HTML5, CSS3, JavaScript.
* **Rendering 3D/2D:** (Esempio: Three.js o Canvas API) per le animazioni dei meccanismi.
* **Motore di Calcolo:** Algoritmi di fisica applicata per la stima dell'autonomia e della portanza.

---

## Installazione

Se desideri eseguire il progetto localmente:

1. Clona la repository:
   ```bash
   git clone [https://github.com/tuo-username/ornithosim.git](https://github.com/tuo-username/ornithosim.git)
