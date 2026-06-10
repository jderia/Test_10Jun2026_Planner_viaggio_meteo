# API

In questo progetto uso la API Open-Meteo.

## Nome API

Open-Meteo Forecast API

## A cosa serve

La API serve per prendere le previsioni meteo delle città scelte.

Le città usate nel progetto sono:

* Lisbona
* Atene
* Nairobi

## Endpoint usato

Lo script usa questo indirizzo base:

https://api.open-meteo.com/v1/forecast

Poi aggiunge latitudine e longitudine della città.

## Dati usati

Nel progetto uso questi dati:

* temperatura massima
* temperatura minima
* probabilità di pioggia

## Dove si vedono i dati

I dati si vedono nella pagina:

destinazioni.html

## Fallback

Se la API non funziona, il sito prova a usare il file:

data.json

In questo file ci sono dati di riserva scritti nel progetto.
