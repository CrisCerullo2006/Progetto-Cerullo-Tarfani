# Progetto-Cerullo-Tarfani
Lavoro di coppia di TPS tra Cristian Cerullo e Vittoria Tarfani

## Descrizione
Questo progetto è un simulatore di combattimento GDR (Gioco di Ruolo) a turni sviluppato in Java. Il sistema si basa sulle meccaniche dei dadi a 20 facce (D20), dove il risultato del lancio determina il successo o il fallimento delle azioni del giocatore. Il gioco include una gestione avanzata delle statistiche, classi personalizzabili, mondi con lore specifica e un'interfaccia grafica (GUI) interattiva.

## Caratteristiche Principali
- **Sistema di Classi:** Scelta tra Guerriero, Mago e Ladro, ognuno con 10 statistiche uniche (HP, MP, Forza, Intelligenza, Destrezza, Fortuna, Agilità, Difesa, Arcano, Iniziativa).
- **Meccanica D20 (SecureRandom):**
  - **1 (MISS):** L'attacco fallisce completamente.
  - **20 (CRITICAL HIT):** Danno raddoppiato (40 HP fissi).
  - **2-19:** Danno calcolato in base al lancio del dado e ai moltiplicatori delle statistiche di classe.
- **Esplorazione Mondi:** Due mondi disponibili ("Cimitero Dimenticato" e "Montagna del Drago") con lore dedicata e una progressione di 5 nemici più un Boss finale.
- **Oggetti e Bonus:** - Possibilità di trovare pozioni curative durante i combattimenti.
  - Sistema di "Arma Affine": se l'arma iniziale è compatibile con la classe scelta, il giocatore riceve un bonus permanente ai danni.
- **Interfaccia Grafica:** Sviluppata in Java Swing con log degli eventi in tempo reale.

## Struttura del Codice
Il progetto è diviso in classi separate per rispettare i principi della programmazione a oggetti (OOP):
- `Classe.java`: Definizione delle statistiche base.
- `Player.java`: Gestione dello stato e dei calcoli del giocatore.
- `Nemico.java` / `Mondo.java`: Logica degli avversari e dei livelli.
- `Arma.java`: Gestione dei bonus equipaggiamento.
- `MainGUI.java`: Punto di ingresso dell'applicazione e gestione dell'interfaccia.

## Requisiti
- Java JDK 8 o superiore.

