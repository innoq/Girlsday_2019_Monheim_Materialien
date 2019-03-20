# DIY Piano

Heute werdet ihr ein gezeichnetes Piano mittels MakeyMakey und Scratch in ein funktionsfähiges Musikinstrument verwandeln!

## Folgende Zutaten braucht ihr dafür:
1. Papier und Bleistift für das Tastenfeld
2. 12 Krokodilklemmen und Vebindungsdrähte
3. eine MakeyMakey Platine
4. eine USB Verbindung zwischen eurem Computer und dem MakeyMakey
5. die passenden Steuerungsbausteine im Scratch Editor
6. Pianotöne

## 1.Das Tastenfeld
Damit ihr das Piano nachher auch spielen könnt, braucht ihr natürlich auch eine Möglichkeit eure Finge zu platzieren..
In der Softwareentwicklung spricht man dabei auch vom "Human Interface" oder der "Mensch und Computer Interaktion".
Euer Tastenfeld zeichnet ihr mit dem Bleistift auf's Papier. Anders als bei einem echten Piano, wo die Tasten dicht nebeneinander liegen,
müsst ihr bei dem DIY Piano darauf achten, dass sich die Konturen eurer ausgemalten Tasten nicht berühren. Lasst also etwas Platz zwischen den einzelenen Tasten. Ein echtes Piano hat außerdem weiße und schwarze Tasten, da ihr aber mit Bleistift zeichnet, werden beim DIY Piano alle Tasten schwarz sein. Insgesamt gibt es 7 Ganztöne (C bis B) und 5 Halbtöne (C# bis A#)
Zur Hilfe gibt es hier eine Übersicht : **_<img einfügen_**

**_oder alterantiv selbst suchen lassen? als miniproblem_**
Wenn du dich nicht mehr genau erinnerst, in welcher Reihenfolge die Noten auf einem Piano angeordent sind, suche dir eine Vorlage aus dem Inertnet.

## 2. Die Krokodilklemmen
An jede Taste des Tastenfeldes wird nun ein Ende einer Krokodilklemme geklemmt. Welches Ende du nimmst, ist egal.

## 3. Der MakeyMakey
Das andere Ende der Krokodilklemme wird nun an bestimmten stellen der Platine geklemmt.
Wir nutzen dabei die Verbindungstellen für die Tasten WASDFG, die Pfeiltasten sowie die Leertaste.
Wenn ihr euch den MakeyMakey genau anseht, werdet ihr diese Stellen finden und bemerken, dass sie unterschiedlich verbunden werden müssen.
An einige dieser Stellen, könnt ihr die Krokodilklemme direkt anschließen. Bei anderen müsst ihr euch eine Brücke überlegen.
Schaut euch dazu eure restlichen Materialien noch einmal genauer an.

## 4.  Die USB Verbindung
Bisher habt ihr folgendes erreicht: Die Pianotasten sind mit den Klemmen verbunden und die Klemmen mit dem MakeyMakey. Nun fehlt noch die Verbindung des MakeyMakey an den Computer. Das geht ganz leicht über den USB-Anschluss. Sobald der Computer den MakeyMakey registriert hat, kann er Eingabe-Signale an euren Computer senden. Die Eingabesignale entstehen, wenn ihr eine gezeichnete Pianotaste berührt.
**_note: erdung wird erst später erwähnt?um dann die magic zu entmysifizieren oder wird davon schon in einem anderen teil geredet??_**

## 5. Die Steuerung
Der MakeyMakey kann nun Eingabesignale senden, aber was soll der Computer damit anfangen? Wie soll er auf welche Eingabe reagieren?
Genau das könnt ihr nun mit Scratch festlegen. Dazu müsst ihr euch die Verbindungen zwischen euren Pianotasten und den MakeyMakey Verbindungspunkten anschauen. Welche Pianotaste führt wo hin? Am besten schreibt ihr euch eine Übersicht auf Papier auf.
Dann könnt ihr mit den Bausteinen in Scratch gezielt auf die Eingabe reagieren.

Ein Beispiel:
Wenn die Pianotaste 'C' mit der Stelle 'W' am MakeyMakey verbunden ist, dann sendet er 'W' an deinen Computer.
In deiner Übersicht könntest du dir z.B. merken: C -> W.

Mit Scratch kannst du nun gezielt steuern, was passieren soll, wenn ein 'W' als Eingabesignal ankommt.
Bestimmt möchtest du, dass ein bestimmter Ton, nämlich der Ton C gespeilt wird.
Probiere aus, welche Bausteine dir dabei helfen könnten.
Vielleicht fällt dir ein, in welcher Kategorie sie sich befinden könnten?


## 6. Die Töne
Die Töne für das Piano müsst ihr euch glücklicherweise nicht einzeln im Internet zusammensuchen, denn Scratch bietet euch eine ganze Sammlung verwendbarer Töne an. Dazu navigiert ihr oberhalb des Editorfensters in den Tab "Klänge". Unten links findet ihr ein kleines Laustprecher-Icon. Wenn ihr den Mauszeiger darüber legt, öffnet sich ein kurzes Menü. Mit einem Klick auf die Lupe öffnet ihr die Klangsammmlung. Hier findet ihr alle Töne, die ihr braucht, mit Ausnahme der Halbtöne.
Wie könntet ihr diese in eurem Code trotzdem erzeugen?
