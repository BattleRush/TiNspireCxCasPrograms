vector2punkte(endP, anfangP)
- Erstellt Vektor aus EndPunkt und AnfangsPunkt
- Eingabe: vector2punkte([x,y,z],[x,y,z])

betrag(vektor)
- Berechnet Betrag vom Vektor
- Eingabe: betrag([x,y,z])

mitte2punkte(punktA, punktB)
- Berechnet Mitte von 2 Vektoren
- Eingabe: mitte2punkte([x,y,z],[x,y,z])

skalarp(vektorA, vektorB)
- Berechnet das SkalarProdukt
- Eingabe: skalarp([x,y,z],[x,y,z])

skalarwinkel(vektorA, vektorB)
- Berechnet Winkel zwischen 2 Vektoren
- Eingabe: skalarwinkel([x,y,z],[x,y,z])

geradengleich(vektorA, vektorB)
- Erstellt Geradengleichung von 2 Vektoren
- Eingabe: geradengleich([x,y,z],[x,y,z])

geradeschneidP(punktA, RichtunA, punktB, RichtungB)
- Gibt Auskunft über Status der 2 Geraden
- Eingabe: geradeschneidP([x,y,z], [x,y,z], [x,y,z], [x,y,z])
- A -> 1. Geraden Gleichung, B -> 2. Gleichung

fusspunkt(punkt, richtung, punktP)
- Berechnet den Fusspunkt vom PunktP zu einer Gerade
- punkt und richtung ist die Geradengleichung
- Eingabe: fusspunkt([x,y,z], [x,y,z], [x,y,z])

punktgeradeabst(richtung, punkt)
- Berechnet Abstand zwischen Punkt und Gerade
- Eingabe: punktgeradeabst([x,y,z], [x,y,z])
- richtung ist nur die Richtungs komponente

abst2geraden(punktA, richtungA, punktB, richtungB)
- Eingabe: abst2geraden([x,y,z], [x,y,z], [x,y,z], [x,y,z])
- Ähnliche Eingabe wie geradeschneidP

fusspunktegerad(punktA, richtungA, punktB, richtungB)
- Berechnet beide Fusspunkte bei windschiefen Geraden
- 2 Geradengleichungen
- Eingabe fusspunktegerad([x,y,z], [x,y,z],[x,y,z], [x,y,z])

hnf(a,b,c,d,punkt)
- EbenenGleichung ax+by+cz+d=0
- Eingabe: hnf(a,b,c,d,[x,y,z])
- Suche Abstand von Ebene zum Punkt

ebenenormalform(vektorA, vektorB, punkt)
- Erstellt Ebenengleichung aus 2 Vektoren und benutzt einen Punkt um "d" zu bestimmen
- Eingabe: ebenenormalform([x,y,z], [x,y,z], [x,y,z])

ebenencrossgerad(a,b,c,d,punkt,richtung)
- Bestimmt den Ort wo die Gerade die Ebene Schneidet
- EbenenGleichung ax+by+cz+d=0
- 2 Vektoren in from einer Geradengleichung
- Eingabe(a,b,c,d,[x,y,z],[x,y,z])

ebenegeradwink(a,b,c,richtung)
- Bestimmt den Winkel den ein Richtungsvektor eine Ebene schneidet
- EbenenGleichung ax+by+cz+d=0
- d wird nicht benötigt
- Eingabe(a,b,c,[x,y,z])

punktspiegebene(a,b,c,d,punkt)
- Spiegelt einen Punkt an einer Ebene
- EbenenGleichung ax+by+cz+d=0
- Eingabe punktspiegebene(a,b,c,d,[x,y,z])

istpunktimkreis(mitteKreis,radius,punkt)
- Bestimmt die Position eines Punktes relativ zum Kreis
- WICHTIG: m ist der MittelPunkt des Kreises!!!
- Radius ist im Quadrat -> Nicht Wurzel ziehen (r^(2)= 36, r = 6 -> Eingabe 36)
- Eingabe: istpunktimkreis([x,y,z],r,[x,y,z])

linkreisschnit(mitteKreis,radius,punkt, richtung)
- Berechnet Schnittpunkte von Gerade und Kreis
- WICHTIG: m ist der MittelPunkt des Kreises!!!
- Radius ist im Quadrat -> Nicht Wurzel ziehen (r^(2)= 36, r = 6 -> Eingabe 36)
- punkt und richtung ist die Geradengleichung
- Eingabe: linkreisschnit([x,y,z],r,[x,y,z], [x,y,z])

tangentekreis(mitteKreis,radius,punkt)
- Berechnet Tangentengleichung an einem Kreis bei bestimmten Punkt
- WICHTIG: m ist der MittelPunkt des Kreises!!!
- Radius ist im Quadrat -> Nicht Wurzel ziehen (r^(2)= 36, r = 6 -> Eingabe 36)
- Eingabe tangentekreis([x,y,z],r,[x,y,z])

version()
- Info über die aktuelle Version