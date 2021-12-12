#Loxone Concept

> Loxone Konzept Wohnhaus "Casa Kubasa" (C) Andreas Kubasa & Jennifer Kubasa

## Windfang
### Funktionen
- Beim reinkommen soll licht angehen und Willkommen (durch den NFC chip erkennbar) gesprochen werden: "Willkommen zu Hause Jennifer"
- Wenn Andreas Kubasa (bestimmte Person) länger als 8 Stunden den NFC schlüssel nicht benutzt hat, soll durchsage: "Dein Kaffee ist in 5 Minuten für dich bereit Andreas" durchsagen und ein Kaffee in 5 Minuten gemacht werden (Home Connect), aufhaltbar indem man beim reingehen einmal auf den Taster im Eingang klickt.

**3-fach Klick**
- lässt Türglocke nicht mehr funktionieren
- stellt Außen auf Scharf
- dreht die Kaffeemaschine ab (Home Connect)
- dreht den Ofen ab (Home Connect)
- dreht den Geschirrspüler ab (Home Connect)

**4-fach Klick**
- kurzen Statusbericht geben: "Heute lieferte die Photovoltaik "so und so viel" Strom, Morgen wird schönes Wetter etc.

## WC
Soll so wirken als wenn man in den Wald auf die Toilette geht
### Tag
- Licht: 60%
- Lautsprecher: 12%
- Nachlaufzeit: 60 Sekunden+

Wenn man reingeht, vogelgeräusche (playlist vogel geräusche etc.) abspielen mit 12% lautsprecher
Wenn keine Bewegung, Lautsprecher stufenweise alle 5 sekunden 1% leiser = 12% -> 0%
Wenn Bewegung, Aktor relais (Spiegel) einschalten *

### Nacht
- Licht: 60%
- Lautsprecher: 12%
- Nachlaufzeit: 60 Sekunden

Wenn man reingeht, licht an wenn, Grillengeräusche (playlist grillen geräusche etc.) abspielen mit 12% lautsprecher
Wenn keine Bewegung, stufenweise nach 30 sekunden jede Sekunde 2% weniger = licht 60% -> 0%
Wenn keine Bewegung, Lautsprecher stufenweise alle 5 sekunden 1% leiser = 12% -> 0%

## Technikraum
- Präsenzerkennung Licht
- Waschmaschine geht an wenn Photovoltaik genug Leistung (Home Connect)

## Wohnzimmer
### Funktionen
- Präsenzmelder tut nichts (Alarmanlage)
- Geteilte Jalousie soll immer aufgehen, wenn man die Terrassentür öffnet

## Küche
### Funktionen
- Präsenzmelder schaltet Licht ein (Schwellenwert, erst wenn man wirklich in der Küche steht)
- Jalousie soll standardmäßig leicht gekippte lammelen haben (blickdicht)
- Jalousie soll immer aufgehen, wenn man die Terrassentür öffnet
- Licht soll angehen wenns dunkel ist und Backofen oder Dampfgarer fertig ist (Home Connect)
- Lautsprecherdurchsage Backofen oder Dampfgarer fertig (Home Connect)
- Geschirrspüler soll sich erst einschalten wenn Photovoltaik genug Leistung bringt, bevorzugt wenn das Haus verlassen wurde (Home Connect + Modbus Zähler)
- Wenn Kaffeemaschine fertig ist mit einem Kaffee, durchsage: "Genießen Sie Ihren frisch gebrühten Kaffee" (Home Connect)

## Esszimmer
### Funktionen
- Jalousie soll immer aufgehen, wenn man die Terrassentür öffnet
- Wenn Präsenz durch Bewegung am Tisch erkannt (Schwellenwert); Pendulums gehen an wenn dunkel
**4-fach Klick**
- schaltet Klassische Musik (Playlist) in der Küche und Esszimmer ein

## Badezimmer
### Funktionen
- Präsenzerkennung Licht einschalten

## Gang
### Funktionen
- Präsenzerkennung Licht einschalten

## Kinderzimmer 1
### Funktionen
- Präsenzerkennung Licht einschalten

## Kinderzimmer 2
### Funktionen
- Präsenzerkennung bestimmte Stimmung einschalten

## Schlafzimmer
### Funktionen
- Präsenzerkennung Licht einschalten
- Wenn Terrassentür geöffnet wird, Jalousien nach oben fahren
- Wenn Terrassentür gekippt wird dann Jalousien kippen falls geschlossen
**3-fach Klick**
- lässt Türglocke nicht mehr funktionieren
- stellt außen auf Scharf
- dreht die Kaffeemaschine ab
- dreht den Ofen ab
- dreht den Geschirrspüler ab
**Wecker** 
- Jalousien kippen
- Waldgeräusche (Playlist) in der Kühlperiode der Heizung abspielen und 
- Schneegetöse (Playlist) in der Heizperiode
