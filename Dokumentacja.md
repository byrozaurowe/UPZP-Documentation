# UPZP Dokumentacja

## Spis treści
* [Opis](#opis)
* Komponenty
  * [Frontend](Frontend.md)
  * [Główny serwer](GlownySerwer.md)
  * [Podproces](Podproces.md)
  * [Statystyki](https://github.com/RideTheSkyP/Team-project-MMO-RPG-Website/blob/master/docs/stats-readme.md)
* [Serializacja](#serializacja)

## Opis
UPZP jest drużynową grą MMO, bazującą na danych z OpenStreetMap. Polega na zbieraniu punktowanych przedmiotów, poruszając się po mapach największych miast świata.
	
## Serializacja
Do serializacji danych przesyłanych pomiędzy klientem, serwerem i podprocesem została wykorzytsana biblioteka FlatBuffers. Więcej informacji [tutaj](https://google.github.io/flatbuffers/).

## Protokół komunikacji
Schemat protokołu komunikacji pomiędzy klientem, serwerem i podprocesem znajduje się [tutaj](Protoko_komunikacji_serwer_-_klient (3).pdf). Natomiast wersje protokołu [tutaj](versions.txt).
