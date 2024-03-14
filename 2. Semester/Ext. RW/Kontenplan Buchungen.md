
## Warenverkehr

3-S#3-27

| Konto | Beschreibung                     |
| ----- | -------------------------------- |
| 390   | Handelsware WEK                  |
| 410   | Wareneinsatz zu Einstandspreisen |
| 830   | Umsatzerlöse eig. Produktion     |
| 850   | Umsatzerlöse Handelsware WVK     |
| 890   | Umsatzerlöse UE/FE               |

Bruttomethode:
1. 410/390: Übertrag WEK in Wareneinstand
2. 989/410: Übertrag Wareneinstand in GuV 
3. 850/989: Übertrag WVK in GuV

Boah, ist das direkt

Nettomethode:
1. 410/390: Übertrag WEK in Wareneinstand
2. 850/410: Saldierung Wareneinstand in WVK
3. 850/989: Übertrag in GuV

Ned so effizient

## Lohn & Gehalt

3-S#3-42

| Konto | Beschreibung             |
| ----- | ------------------------ |
| 171   | Einbehaltene Steuern     |
| 172   | Einbehaltene SV-Beiträge |
| 430   | Löhne und Gehälter       |
| 440   | AG-Anteil SV-Beiträge    |

Generell Buchungen:
1. 430/113: Überweisen der Gehälter
2. 430/172: Einbehaltene AN-SV-Beiträge
3. 430/171: Einbehaltene Steuern
4. 440/172: Einbehaltene AG-SV-Beiträge


## Abschreibungen Anlagen

3-S#3-46

| Konto | Beschreibung                   |
| ----- | ------------------------------ |
| 80    | Wertberichtigungen auf Anlagen |
| 230   | Abschreibungen                 |

### Direkt
Abschreibung wird direkt im Konto gebucht, für das die Abschreibung vorgenommen wird, also z.B.:
- 230/10 für eine Abschreibung einer Maschine

### Indirekt
Abschreibung wird in Passiv-Konto gebucht, das alle Abschreibungen "sammelt":
- 230/80

## Pauschalwertberichtigungen PWB

3-S#3-51

| Konto | Beschreibung                        |
| ----- | ----------------------------------- |
| 140   | Forderungen L+L                     |
| 141   | Dubiose Forderungen                 |
| 159   | PWB Forderungen                     |
| 221   | Aufwand aus periodenfremder Ursache |
| 226   | Erträge aus Herabsetzen PWB         |
| 232   | Einstellungen PWB                   |

### Bildung PWB:
1. 232/159

### Korrigieren ausgefallene Forderungen:
1. 159/141 (bzw. 140): Korrektur der Forderung durch PWB

3 Fälle:
- A: PWB zu wenig
- B: PWB zu viel
- C: PWB passt genau

### Fall A: Falls PWB zu wenig:
2. 221/141 (bzw. 140): Korrektur der Forderung als Rest

### Fall B: Falls PWB zu viel:
2. 159/226: Rest PWB als Ertrag buchen

### Korrektur Ust:
3. 175/141 (bzw. 140): Korrektur USt. 

## Abschreibungen Forderungen

3-S#3-46

| Konto | Beschreibung                        |
| ----- | ----------------------------------- |
| 140   | Forderungen L+L                     |
| 141   | Dubiose Forderungen                 |
| 221   | Aufwand aus periodenfremder Ursache |
| 233   | Abschreibungen auf Forderungen      |

Generell Forderungen selbe Periode:
1. 141/140: Überschreiben Forderung nach dubiose Forderung
2. 233/141: Abschreiben der dubiosen Forderung
3. 175/141: Abschreiben USt. der dubiosen Forderung

Generell Forderungen frühere Periode:
1. (141/140: Überschreiben Forderung nach dubiose Forderung) (schon irgendwann passiert)
2. 221/141: Abschreiben der dubiosen Forderung als Aufwand aus periodenfremder Ursache
3. 175/141: Abschreiben USt. der dubiosen Forderung

## Privatkonto

3-S#3-55

| Konto | Beschreibung                        |
| ----- | ----------------------------------- |
| 190   | Privat                              |

## Rechnungsabgrenzungsposten

3-S#4-5

| Konto | Beschreibung                                 |
| ----- | -------------------------------------------- |
| 98    | Aktive Rechnungsabgrenzung (trans. Aktiva)   |
| 99    | Passive Rechnungsabgrenzung (trans. Passiva) |
| 158   | Sonst. Forderungen (antizip. Aktiva)         |
| 159   | Sonst. Verbindlichkeiten (antizip. Passiva)  |
### ARAP
Z.B.: Wir zahlen Miete im Voraus

Jahr 1:
1. 470/113: Bezahlen von Miete altes Jahr
2. Ende des Jahres:
	1. 098/470: Bilden ARAP
	2. 989/470: Übertrag in GuV
	3. 999/098: Übertrag in SB

Jahr 2:
1. 470/098: Bezahlen von Miete neues Jahr aus ARAP

## Rückstellungen

3-S#4-10

| Konto | Beschreibung          |
| ----- | --------------------- |
| 88    | Sonst. Rückstellungen |



