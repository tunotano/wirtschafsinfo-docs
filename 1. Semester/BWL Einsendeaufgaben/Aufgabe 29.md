#Produktionsprogrammplanung #Deckungsspanne #Unklar

Ein Unternehmen kann die Produkte 1 und 2 herstellen und benötigt dazu die potentiell knappen Rohstoffe A und B. Sie werden von der Unternehmensführung mit der Planung des optimalen Produktionsprogramms beauftragt. Dazu erhalten Sie die in nachstehender Tabelle wiedergegebenen Daten über die Produktionskoeffizienten $\large{PK_{ij}}$, welche den Verbrauch an Rohstoffeinheiten des Rohstoffes i zur Produktion einer Mengeneinheit des Produktes j angeben, über die Absatzpreise $\large{p_{j}}$ und Absatzhöchstmengen $\large{x_{j}^{max}}$ der Produkte j sowie über die Beschaffungspreise $\large{q_{i}}$ und maximal verfügbaren Mengen $\large{y_{i}^{max}}$ der Rohstoffe i. Die fixen Kosten $\large{K_{fix}}$ der Periode betragen 6000 Geldeinheiten \[GE\].

|                    | A    | B    | Absatzhöchstmenge | Absatzpreis |
| ------------------ | ---- | ---- | ----------------- | ----------- |
| Produkt 1          | 6    | 4    | 200               | 120         |
| Produkt 2          | 3    | 8    | 100               | 150         |
| Verfügbare Menge   | 1800 | 1400 |                   |             |
| Beschaffungspreise | 8    | 11   |                   |             |

Daneben erhalten Sie folgende hilfreiche Informationen:

Deckungsspannen: DS1 = 28, DS2 = 38 GE/ME.
Kapazitätsbeanspruchungen der Rohstoffe: yA = 1500, yB = 1600 FE.
Wertmäßige Deckungsspannen: WDS1 = 9, WDS2 = 0 GE/ME.  
Deckungsbeitragsmaximales Produktionsprogramm: x1 = 200, x2 = 75 ME.  

Wie hoch sind der zugehörige maximale Gesamtdeckungsbeitrag und der Gewinn?

Gesamtdeckungsbeitrag: GDB = Antwort.
Gewinn: G = Antwort.  

(Eingabe ohne Tausendertrennzeichen!)

GDS = $\large{DS_{1} * x_{1} + DS_{2} * x_{2} = 28 * 200 + 38 * 75 = 8450}$  
Gewinn = $\large{GDS - K_{fix} = 8450 - 6000 = 2450}$  

Restliche Zahlen zur Übung:

Deckungsspannen:
$\large{DS_{1} = 120 - (6 * 8 + 4 * 11) =  28}$  
$\large{DS_{2} = 150 - (3 * 8 + 8 * 11) =  38}$  
$\Rightarrow$ Beide Deckungsspannen sind vorteilhaft

Engpässe:  
$\large{y_{A} = 6 * 200 + 3 * 100 = 1500 < 1800}$ $\Rightarrow$ Kein Engpass  
$\large{y_{B}= 4 * 200 + 8 * 100 = 1600 > 1400}$ $\Rightarrow$ Möglicher Engpass  

Relative Kapazitätsbeanspruchungen sind egal, weil wir wissen, dass der Engpass nur bei Faktor B entstehen wird.

Relative Deckungsspannen:  
$\large{RDS_{1B} = {28 \over 4} = 7}$ $\Rightarrow$ Rang 1  
$\large{RDS_{2B} = {38 \over 8} = 4.75}$ $\Rightarrow$ Rang 2  

Dadurch, dass Produkt 1 eine höhere relative Deckungsspanne aufweißt, produzieren wir zuerst die volle Absatz-Höchst-Menge an Produkt 1.  
Produkt 1 verbraucht bei 200 Einheiten $\large{4 * 200 = 800}$ Einheiten von Faktor B, d.h. es bleiben noch $\large{1400 - 800 = 600}$ Einheiten über, mit denen Produkt 2 hergestellt werden kann.  
Produkt 2 benötigt 8 Einheiten von Faktor B, weswegen maximal $\large{600 : 8 = 75}$ Einheiten von Produkt 2 hergestellt werden können.

Der Deckungsbeitragsmaximale Produktionsplan ergibt sich somit zu: 

| Produkt | Einheiten |
| ------- | --------- |
| A       | 200       |
| B       | 75        |

