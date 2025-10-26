# LinoxCorsoRPI2015

Materiale didattico e slide per il corso "Costruiamo la nostra Stazione Meteo" tenuto a Novara (12 Feb 2015) da Matteo Baccan, con la collaborazione di Valerio Tognozzi per la parte hardware.

Questo repository contiene le slide in formato PDF e ODP suddivise in 3 parti, più il materiale di supporto per l'installazione e la configurazione di un Raspberry Pi per uso server, mediacenter e come stazione meteo.

## Contenuti principali

- Introduzione a Raspberry Pi: cos'è, modelli, componenti hardware e prezzi.
- Prima configurazione: NOOBS, Raspbian, raspi-config, aggiornamenti e pulizia del sistema.
- Uso come server: LAMP (Apache, MySQL, PHP), Webmin e ottimizzazioni per velocità e memoria.
- Stazione meteo: sensori Adafruit (BMP085 etc.), esempi Python per lettura dati e inserimento in MySQL.
- Frontend di visualizzazione: uso di Bootstrap, jQuery, Flot, Font Awesome e MetisMenu per mostrare i dati raccolti.
- Creazione di un Raspberry Pi virtuale con QEMU per testare senza hardware reale.

## Sommario dei documenti

- Parte 1 — Panoramica su Raspberry Pi
  - Introduzione al progetto Raspberry Pi e alle versioni disponibili (A, B, A+, B+, 2).
  - Componenti hardware, prezzi indicativi e consigli per l'hardware (alimentatore, SD classe 10, hub USB, adattatori HDMI/VGA, wifi USB).
  - Panoramica su NOOBS, Raspbian e alternative (OpenELEC, retrogaming, pwnpi).
  - Tecniche di ottimizzazione: overclock, memory split (gpu_mem), riduzione delle sessioni terminale e rimozione di servizi.

- Parte 2 — Setup e Stazione Meteo
  - Prima configurazione: utente/credenziali di default (utente: pi, password: raspberry), impostazioni locali via `raspi-config`.
  - Aggiornamenti APT, rimozione di pacchetti pesanti (es. `wolfram-engine`) e comandi di pulizia (`autoremove`, `clean`).
  - Installazione stack LAMP e suggerimenti per ottimizzazioni lato server.
  - Sensori utilizzati (Adafruit BMP085 e altri), esempi di script Python per leggere sensori e salvare dati in MySQL.
  - Guida rapida alla creazione di un Raspberry Pi virtuale con QEMU.

- Parte 3 — Frontend e visualizzazione dati
  - Realizzazione di un frontend basato su Bootstrap, uso di jQuery, Flot per grafici, Font Awesome e MetisMenu per la navigazione.
  - Esempi di integrazione tra i dati acquisiti dai sensori e la visualizzazione web.

## File nel repository

I file principali presenti nella cartella di lavoro sono:

- `Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_1.pdf`
- `Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_1.odp`
- `Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_2.pdf`
- `Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_2.odp`
- `Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_3.pdf`
- `Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_3.odp`

## Link ai documenti (PDF / ODP)

- Parte 1: [PDF](./Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_1.pdf) | [ODP](./Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_1.odp)
- Parte 2: [PDF](./Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_2.pdf) | [ODP](./Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_2.odp)
- Parte 3: [PDF](./Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_3.pdf) | [ODP](./Matteo_Baccan_-_Raspberry_Pi_-_Linox_2015_-_corso_parte_3.odp)

## Note e contatti

Per richieste di aggiornamento o integrazioni al materiale, aprire un issue o contattare l'autore.
