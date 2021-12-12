#Loxone Concept

> Loxone Konzept Wohnhaus "Casa Kubasa" (C) Andreas Kubasa & Jennifer Kubasa

## Windfang
### Funktionen
- Beim reinkommen soll (durch den NFC chip erkennbar) das Licht angehen und ein individueller Text gesprochen werden: "Willkommen zuhause Jennifer"
- Wenn Andreas Kubasa (bestimmte Person) länger als 8 Stunden zuhause nicht Anwesend war soll beim betretten des Hauses (durch nutzen des NFC Schlüssels) eine Durchsage: "Dein Kaffee ist in 5 Minuten für dich bereit Andreas" starten und fünf Minuten später soll ein Befehl an die Kaffeemaschine gegeben werden einen Kaffee zu machen (Home Connect), aufhaltbar indem man beim reingehen einmal auf den Taster im Eingang klickt.

**3-fach Klick** 
- alle Lichter und Lautsprecher gehen aus
- lässt Türglocke nicht mehr funktionieren
- stellt Außen auf Scharf
- dreht die Kaffeemaschine ab (Home Connect)
- dreht den Ofen ab (Home Connect)
- dreht den Geschirrspüler ab (Home Connect)

**4-fach Klick**
- kurzen Statusbericht geben: "Heute lieferte die Photovoltaik "so und so viel" Strom, Morgen wird schönes Wetter, die durchschnittliche Luftfeuchtigkeit ist..., da und dort gibt es Probleme (z.B., Raum Badezimmer - Luftfeuchtigkeit zu hoch, morgen Hagel) etc.

## WC
Soll so wirken als würde man im Wald auf der Toilette sitzen
-Präsenzerkennung Licht einschalten
### Tag
- Licht: 60%
- Lautsprecher: 12%
- Nachlaufzeit: 60 Sekunden+

Beim betreten, Vogelgeräusche (Playlist Vogelgeräusche etc.) abspielen mit 12% Lautstärke über den Lautsprecher
Wenn keine Bewegung Lautsprecher stufenweise alle 5 sekunden 1% leiser = 12% -> 0%
Wenn Bewegung Aktor Relais (Spiegel) einschalten *

### Nacht
- Licht: 60%
- Lautsprecher: 12%
- Nachlaufzeit: 60 Sekunden

Beim betreten, Licht an, Grillengeräusche (Playlist Grillengeräusche etc.) abspielen mit 12% Lautstärke über den Lautsprecher
Wenn keine Bewegung stufenweise nach 30 sekunden jede Sekunde 2% weniger = licht 60% -> 0%
Wenn keine Bewegung Lautsprecher stufenweise alle 5 sekunden 1% leiser = 12% -> 0%

## Technikraum
- Präsenzerkennung Licht einschalten
- Waschmaschine geht an wenn Photovoltaik genug einspeist ( Home Connect, Modbuszähler)

## Wohnzimmer
### Funktionen
- Präsenzmelder steuert nichts (Einzig für Präsenzerkennung bezüglich der Heizung und für die Alarmanlage)
- Jalousie (nur die Türjalousin der geteilten Jalousien) soll immer aufgehen, wenn man die Terrassentür öffnet

## Küche
### Funktionen
- Präsenzmelder schaltet Licht ein (Schwellenwert, erst wenn man wirklich in der Küche steht)
- Jalousie soll standardmäßig leicht gekippte Lammelen haben (Blickdicht)
- Jalousie soll immer aufgehen, wenn man die Terrassentür öffnet
- Licht soll bei Dunkelheit angehen wenn Backofen oder Dampfgarer fertig ist (Home Connect)
- Lautsprecherdurchsage Backofen oder Dampfgarer fertig (Home Connect)
- Geschirrspüler soll sich erst einschalten wenn Photovoltaik genug einspeist, bevorzugt wenn das Haus verlassen wurde (Home Connect + Modbuszähler)
- Wenn Kaffeemaschine mit Kaffee fertig ist, durchsage: "Genießen Sie Ihren frisch gebrühten Kaffee" (Home Connect)

## Esszimmer
### Funktionen
- Jalousie soll immer aufgehen, wenn man die Terrassentür öffnet
- Wenn Präsenz durch Bewegung am Tisch erkannt (Schwellenwert); gehen die Pendulums bei Dunkelheit an
**4-fach Klick**
- schaltet Klassische Musik (Playlist) in der Küche und Esszimmer ein

## Badezimmer
### Funktionen
- Präsenzerkennung Licht einschalten
- Luftfeuchtigkeitsmesser Durchsagen (zu hoch soll einfach Lautsprecher Wellenrauschen (Playlist) weiter abspielen, "Fenster kann geschloßen werden, Luftfeuchtigkeit wieder im Normalbereich)
### Tag
- Licht: 60%
- Lautsprecher: 12%
- Nachlaufzeit: 60 Sekunden+

Beim betreten, Meeresrauschen (Playlist Meeresrauschen etc.) abspielen mit 12% Lautstärke über den Lautsprecher
Wenn keine Bewegung Lautsprecher stufenweise alle 5 sekunden 1% leiser = 12% -> 0%
Wenn Bewegung Aktor Relais (Spiegel) einschalten *

### Nacht
- Licht: 60%
- Lautsprecher: 12%
- Nachlaufzeit: 60 Sekunden

Beim betreten, Licht an, Meeresrauschen (Playlist Meeresrauschen etc.) abspielen mit 12% Lautstärke über den Lautsprecher
Wenn keine Bewegung stufenweise nach 30 sekunden jede Sekunde 2% weniger = licht 60% -> 0%
Wenn keine Bewegung Lautsprecher stufenweise alle 5 sekunden 1% leiser = 12% -> 0%

## Gang
### Funktionen
- Präsenzerkennung Licht einschalten

## Kinderzimmer 1
### Funktionen
- Präsenzerkennung Licht einschalten
- wird manuell eingegriffen z.B.: durch Licht abdrehen wenn man sich im Raum befindet(Präsenzerkennung) bleibt es auf Manuell, verlässt man den Raum für eine Stunde soll wieder auf Automatik gestellt werden 

## Kinderzimmer 2
### Funktionen
- Präsenzerkennung bestimmte Stimmung einschalten
- - wird manuell eingegriffen z.B.: durch Licht abdrehen wenn man sich im Raum befindet(Präsenzerkennung) bleibt es auf Manuell, verlässt man den Raum für eine Stunde soll wieder auf Automatik gestellt werden 

## Schlafzimmer
### Funktionen
- Präsenzerkennung Licht einschalten
- Jalousie soll immer aufgehen, wenn man die Terrassentür öffnet
- Wenn Terrassentür gekippt wird dann Jalousien kippen falls geschlossen
**3-fach Klick**
- Lichtsteuerung durch Präsenz im Schlafzimmer aus
- lässt Türglocke nicht mehr funktionieren
- stellt außen auf Scharf
- dreht die Kaffeemaschine ab
- dreht den Ofen ab
- dreht den Geschirrspüler ab
- wenn Präsenz nach Aktivierung im Gang erkannt wird zusätzlich Licht Windfang an
- Hellichkeit der Lichter auf 15%
**Wecker** 
- Jalousien kippen
- Waldgeräusche (Playlist) in der Kühlperiode der Heizung abspielen und 
- Schneegetöse (Playlist) in der Heizperiode

## Schrankraum
### Funktionen
- Präsenzerkennung Licht einschalten

## Terrasse
### Funktionen
- bei Dunkelheit durch öffner der Terrassentür Licht einschalten beim schliessen der Twerrassentür wieder abschalten 
