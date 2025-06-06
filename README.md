# Fishing-Spot-Finder

Fishing Spot Finder è un'applicazione web che ti aiuta a trovare i migliori spot di pesca in Italia, con informazioni su:
- Pesci presenti
- Condizioni meteo in tempo reale
- Posizione degli spot su una mappa interattiva

Funzionalità principali

- Filtra per provincia e tipo di pesce
- Visualizza i risultati sulla mappa Google
- Mostra le condizioni meteo aggiornate (OpenWeather API)
- Risultati testuali con nome spot, pesci, meteo e recensioni



Requisiti

- PHP
- Connessione Internet per usare le API
- API Key personali per:
  - OpenWeather
  - Google Maps JavaScript


Come avviare il progetto

1) Scarica il progetto

Copia tutti i file nella tua cartella htdocs di XAMPP:


C:\xampp\htdocs\fishing-spot-finder

2) Inserisci le API Key

 .env.php

Apri il file .env.php e inserisci la tua chiave di OpenWeather:

define('OPENWEATHER_API_KEY', 'API-KEY_OPENWEATHER');

index.html

Cerca questa riga alla fine del file e sostituisci API-KEY con quella di Google Maps:


src="https://maps.googleapis.com/maps/api/js?key=API-KEY&callback=initMap"></script>


3) Avvia Apache

Apri XAMPP e clicca Start su Apache.


4) Apri il progetto nel browser

Vai su:

http://localhost/fishing-spot-finder/index.html

Tecnologie usate: HTML, CSS, JavaScript, PHP, JSON, Google Maps API, OpenWeather API

