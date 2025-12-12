# Frogger C - Operating Systems Project 🐸

Un clone del videogioco arcade *Frogger* scritto interamente in C, sviluppato per il corso di Sistemi Operativi.
Il progetto non è solo un gioco, ma una dimostrazione pratica della gestione di processi, thread e sincronizzazione in ambiente Linux.

## ⚙️ Architettura Tecnica
Il gioco utilizza un'architettura concorrente per gestire le varie entità in movimento (rane, auto, tronchi).

### Caratteristiche Principali:
- **Multithreading & Multiprocessing:** Ogni entità dinamica del gioco (es. i veicoli) è gestita da flussi di esecuzione indipendenti.
- **Sincronizzazione:** Utilizzo di **Mutex** e **Semafori** per evitare Race Conditions e garantire l'accesso sicuro alle risorse condivise (schermo e strutture dati).
- **Libreria ncurses:** Rendering grafico testuale nel terminale per un'esecuzione leggera ed efficiente.

## 🕹 Funzionalità
- Movimento fluido del personaggio.
- Generazione asincrona degli ostacoli.
- Rilevamento delle collisioni in tempo reale.
- Gestione del punteggio e delle vite.

## 👥 Il Team
Questo progetto è stato realizzato in collaborazione accademica da:

* **Franesco Pili** - [GitHub](https://github.com/FranCBrain)
* **Nicola Floris** -
