## Aufgabe 1:

RGB 255/255/255 (Weiss): YCbCr: 1-0-0
RGB 0/0/0 (Schwarz): YCbCr: 0-0-0
YCbCr Werte und deren Farbentsprechungen:
Y:0, Cb:0.5, Cr:0: Rot
Y:0, Cb:-0.5, Cr:0: Grün
Y:0, Cb:0, Cr:0.5: Blau
Y:0, Cb:0, Cr:-0.5: Grün
Y:0.3, Cb:0.5, Cr:-0.17: Rot

## Aufgabe 2:

RGB-Werte (Hellblau): R=33, G=121, B=239

Graustufenwert: 106 (Rot: 33 x 0.3 + Grün: 121 x 0.6 + Blau: 239 x 0.1)

## Aufgabe 3:

50% (Original: 300% Farbinformation, Subsampling: 150%)

## Aufgabe 4:

a. Ja, die Umwandlung von RGB in YCbCr kann Speicherplatz einsparen, besonders durch Subsampling wie 4:2:2 oder 4:2:0.

b. Beamer können Bilder nicht direkt im YCbCr-Farbraum darstellen; sie wandeln das Signal in RGB um.

c. Ein Farbbild wird in ein Graustufenbild umgerechnet mit: Grauwert= 0.299R + 0.587G + 0.114B.

d. Der Grünanteil hat das grösste Gewicht, da das menschliche Auge am empfindlichsten auf grüne Lichtwellen reagiert.

## Aufgabe 5:

a. Keine Verschlechterung, da Luminanzkanal unverändert bleibt.

b. 50%

## Aufgabe 6:

a. Umwandlung von RGB in YCbCr, gefolgt von Subsampling.

b. Keine direkte Datenreduktion, Quantisierung benötigt.

c. Durch 8x8 Block-Quantisierung und anschließende Angleichung der Farbwerte innerhalb der Blöcke.

## Aufgabe 7:

a.

- Intraframe: Komprimiert jedes Bild einzeln.
- Interframe: Komprimiert Unterschiede zwischen aufeinanderfolgenden Bildern.

b.

- Faultier: Mehr Potential wegen geringer Bewegung.
- Formel-1: Weniger Potential wegen hoher Bewegung.

c. Beide speichern nur Änderungen seit der letzten Speicherung.

d. Eine Gruppe von 25 Bildern mit einem vollständigen Referenzbild am Anfang.
