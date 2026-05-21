# THB-Graphical_Visualisation_Technologies Einsendeaufgaben

Einsendeaufgaben für das Modul "Graphical Visualisation Technologies". Ziel des Moduls war es ein Grundverständnis für 3D-Visualisierungen, primär für webbasierte Anwendungen, aufzubauen.

## EA 1 - Interaktiv animierte Scheibe

Implementieren Sie eine sich drehende 2D-Scheibe aus Einzelbildern, welche Sie mit JavaScript laden und in einem <img> Image-Element zeigen (nicht im Canvas). Die Einzelbilder sollen, ähnlich wie bei einer Sprite-Sheet-Animation ode einem Animationsfilm, so ausgetauscht und eingeblendet werden, dass visuell der Eindruck einer Rotation entsteht. Auf jedem Einzelbild ist ein Rotationszustand der Scheibe zu sehen, z. B.: 0°, 15°, 30°,...

// nicht mehr da

## EA 2 - 2D Geometrie aus Linien

Erstellen Sie eine eigene 2D-Geometrie aus Linien (etwa 30 Vertices) und stellen Sie diese mittels WebGL dar. Dabei können Sie GL_LINES, GL_LINE_STRIP oder GL_LINE_LOOP verwenden.

https://lenkuep.github.io/thb-gvt-ea/EA2/

## EA 3 - Farbig gefüllte 2D Geometrie

Kolorieren Sie eine eigene 2D-Geometrie indem Sie nun Dreiecke (keine Linien) erzeugen (Sie können auf der Lösung der vorherigen Aufgabe aufbauen). Sie können dabei einfarbige Flächen oder auch Farbverläufe einsetzen.

https://lenkuep.github.io/thb-gvt-ea/EA3/

## EA 4 - Parametrisierte Flächen

1) Erzeugen Sie zwei neue parametrisierte Flächen (die nicht im Modul vorkommen) zunächst mit Linien, siehe Material (dort gibt es viele Formeln, die Sie verwenden können).

2) Füllen Sie dann die Flächen und kolorieren Sie sie passend zur jeweiligen Flächenform, z. B. mit Farbverläufen. Die Linien sollen noch sichtbar sein, oder es besteht die Möglichkeit, zwischen Linien und Füllung umzuschalten.

3) Kreieren Sie auch eine eigene Parametrisierung für eine Fläche und kolorieren Sie diese. Dazu sollen Sie sich eine neue Formel ausdenken, diese können Sie natürlich auf der Basis der vorhandenen Formeln aufbauen (aus dem Modul oder aus dem Material). Versuchen Sie Terme zu mischen und schauen Sie, ob das passiert, was Sie erwarten. Alternativ suchen Sie sich eine Form und versuchen Sie diese zu erzeugen, vielleicht „eine Qualle“ oder Ihre Lampe (dieses Vorgehen ist meist schwieriger).

https://lenkuep.github.io/thb-gvt-ea/EA4/

## EA 5 - Kamerabewegung

Teil 1: Erstellen Sie eine Szene aus mindestens zwei Grundkörpern oder parametrisierten Flächen. Sie soll interaktiv von allen Seiten einsehbar sein, siehe Interaktion. 

Teil 2: Erstellen Sie ein rekursives Kugel-Modell, wie in Lerneinheit GRU beschrieben. Die Tiefe der Rekursion soll direkt von der Webseite aus interaktiv einstellbar sein. Es hilft zunächst einen Oktaeder zu bauen und auf diesen aufbauend die Dreiecksteilung vorzunehmen. Kolorieren Sie das Modell. Die Linien dabei sollen zusätzlich sichtbar sein, oder es besteht die Möglichkeit zwischen Linien und Füllung umzuschalten. Sie können die Kugel in die Szene aus Teil 1 der Aufgabe integrieren.

https://lenkuep.github.io/thb-gvt-ea/EA5/

## EA 6 - Objekte bewegen - fliegende Kugeln

Lassen Sie die vier Kugeln aus dem Beispielprogramm aus der Lerneinheit TFM interaktiv durch den Torus fliegen. Dabei bewegen sich die Kugeln kontinuierlich auf Kreisbahnen so, dass sie sich nie berühren.

https://lenkuep.github.io/thb-gvt-ea/EA6/

## EA 7 - Z-Buffer Visualisierung

Erstellen Sie eine Szene aus mindestens drei Grundkörpern dar, die einander überschneiden, damit man ihre relative Lage besser einschätzen kann. Stellen Sie den Tiefenbuffer (Z-Buffer), das heißt die Z-Werte der Fragmente im Framebuffer, als Graustufen dar. Die Fragmente, die in Z-Richtung näher an der Kamera sind, sollen dunkler dargestellt werden. In der Szene soll möglichst viel Tiefe erzeugt werden, sodass der Effekt deutlich wird.

https://lenkuep.github.io/thb-gvt-ea/EA7/

## EA 8 - Lichter auf Kreisbahn mit Toon Shading

Erweitern Sie die Aufgabe Bel-3 (oder Bel-2 in schwarz-weiß) aus der Lerneinheit BEL (Kap.14.9).  Auf einen Tastendruck sollen sich die beiden Lichter in der Szene gleichzeitig auf einer Kreisbahn um die Modelle bewegen. Sie bewegen sich unabhängig von der Kamera (nicht wie ein Licht, das fest auf der Kamera montiert ist).

https://lenkuep.github.io/thb-gvt-ea/EA8/

## EA 9 - Torustextur

Texturieren Sie einen Torus mit einer Bildtextur. Dazu müssen zu den Geometriedaten des Torus zunächst Texturkoordinaten hinzugefügt werden.

https://lenkuep.github.io/thb-gvt-ea/EA9/
