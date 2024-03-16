- Gegeben: Forderungssumme auf Konto 140, Ertragskonto + Ust. der Leistung
- Beispielwerte: Forderungsumme: 1000 Euro als WVK (850)


## Cookbook:

### 1. Es wird bekannt, dass Forderungen womöglich nicht bezahlt werden können:

Buchen der Gesamtforderung (Brutto) von 140 (Forderungen) auf 141 (dubiose Forderungen): 141/140 

Beispiel: 
- Buchung: 141/140 1000
### 2. Man bekommt Details, wie wieviel gezahlt werden kann/wie hoch die Ausfallsumme ist:

Forderung in Ausfallhöhe abschreiben. Gebucht wird nur Netto, korrigiert wird die USt. meistens erst später. Die Forderung gilt allerdings in Brutto abgeschrieben (wenn auch nur gedanklich).

Beispiel: 
- Ausfallhoehe: 75%: 750 Euro, d.h. 630.25 Euro werden als abgeschrieben gebucht, 119.75 Euro Ust. sind "abgeschrieben", aber noch nicht korrigiert.
- Buchung: 233/141 630
### 3. Variationen: Es wird eine Zahlung/Vergleichsquote erhalten, die:

1. __Kleiner__ als erwartet ausfällt: Wir haben mit wenigstens 25% der ursprünglichen Forderung gerechnet, erhalten aber weniger. D.h. wir müssen erneut abschreiben.
2. __Höher__ als erwartet ausfällt: Wir haben mit wenigestens 25% der ursprünglichen Forderung gerechnet, erhalten aber mehr. D.h. wir haben zu viel abgeschrieben.

#### Variation 3.1.: Die Vergleichsquote ist __kleiner__ als erwartet

Beispiel: Wir erhalten 150 Euro als Vergleichsquote (erwartet waren 25%, also 250 Euro)
##### 3.1.1. Zahlung verbuchen
Die erhaltene Zahlung wird vollständig in das (dubiose) Forderungskonto gebucht

Beispiel: 113/141 150
##### 3.1.2. USt.-Korrektur ermitteln 
Wir ermitteln, um wie viel wir die bereits gebuchte Umsatzsteuer korrigieren müssen. Der Wert ergibt sich durch den Umsatzsteuerteil der Gesamtforderung - den Umsatzsteuerteil der erhaltenen Zahlung

Beispiel: 
- 1000 Euro Gesamtforderung (Brutto) -> 190 Euro Ust.
- 150 Euro erhaltene Zahlung -> 23.95 Euro Ust
- Korrektur: 190 - 23.95 = 166.05
- Buchung: 175/141 166
##### 3.1.3. Rest der Abschreibung ermitteln
Wir ermitteln den noch abzuschreibenden Rest der Forderung. Dafür nehmen wir die Gesamtforderungssumme und ziehen alle Beträge ab, die das Forderungskonto reduziert haben  (1. Forderungsabschreibung, Ust-Korrektur, Vergleichsquote)

Beispiel:

| Betrag in Euro | Beschreibung                   |
| -------------- | ------------------------------ |
| 1000           | Forderungssumme auf Konto      |
| - 630          | 1. Forderungs-Abschreibung     |
| - 150          | Vergleichsquote                |
| - 166          | Ust.-Korrektur                 |
| 54             | Übrige Forderungs-Abschreibung |

Buchung: 233/141 54

#### Variation 3.2.: Die Vergleichsquote ist __höher__ als erwartet

Beispiel: Wir erhalten 500 Euro als Vergleichsquote (erwartet waren 25%, also 250 Euro)
##### 3.2.1. Ertrag ermitteln
Der Wert, den wir zu viel erhalten haben ist für uns Ertrag aus Periodenfremder Ursache (227). Er ermittelt sich, in dem wir den erhaltenen Betrag von dem erwarteten abziehen und davon die Umsatzsteuer abziehen, da ja die Umsatzsteuer keinen Ertrag für uns darstellen kann.

Beispiel:
- Erhalten: 500 Euro, erwartet: 250 Euro, d.h. Ertrag = 500 - 250 = 250 Euro
- Abzug USt.: 250/1.19 = 210.08 Euro
- Buchung: 113/227 210

##### 3.2.2 USt.-Korrektur ermitteln
Wir ermitteln, um wie viel wir die bereits gebuchte Umsatzsteuer korrigieren müssen. Der Wert ergibt sich durch den Umsatzsteuerteil der Gesamtforderung - den Umsatzsteuerteil der erhaltenen Zahlung

Beispiel: 
- 1000 Euro Gesamtforderung (Brutto) -> 190 Euro Ust.
- 500 Euro erhaltene Zahlung -> 80 Euro Ust
- Korrektur: 190 - 80 = 80
- Buchung: 175/141 80

##### 3.2.3 Rest der Einzahlung ermitteln
Wir ermitteln den Rest, den wir als Teil der erhaltenen Zahlung in das Forderungskonto buchen. Dafür nehmen wir die Gesamtforderungssumme und ziehen alle Beträge ab, die das Forderungskonto reduziert haben (1. Forderungsabschreibung, Ust-Korrektur)

Beispiel:

| Betrag in Euro | Beschreibung               |
| -------------- | -------------------------- |
| 1000           | Forderungssumme auf Konto  |
| - 630          | 1. Forderungs-Abschreibung |
| - 80           | Ust.-Korrektur             |
| 290            | Übrige Forderungsbuchung   |

Buchung: 113/141 290


## Anwendungen:

### Variante 2: Klausur März 21, Aufgabe 1b)
![](_attachments/Pasted%20image%2020240316132728.png)

![](_attachments/Pasted%20image%2020240316132751.png)