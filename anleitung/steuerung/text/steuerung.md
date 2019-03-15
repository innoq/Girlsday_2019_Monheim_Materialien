# Steuerung

# TODO Einleitung

## TODO Du gibst den Ton an!

## Schritte wiederholen
Beim Programmieren möchte man oft Verarbeitungschritte öfter als nur einmal ausführen lassen, ohne denselben Code mehrmals zu schreiben.
Dafür gibt es in Scratch den Baustein "Wiederholung". Wiederholungen werden allgmein auch Schleifen genannt.
Mit Wiederholungen kann man genau das tun, was der Name vermuten lässt: Einen Codeabschnitt mehrmals ausführen lassen.

### Aber wie oft?
Manchmal weiß man das zu Beginn noch nicht genau, wenn man mit dem Programmieren erst neu angefangen hat.
Die einfachste Wiederholung, die du ausprobieren kannst, ist die endlose Wiederholung.
In Scratch heißt dieser Baustein: "wiederhole fortlaufend"
Diese Widerholung findet also so lange statt, bis du das Programm abbrichst.

Eine andere Variante ist "wiederhole x mal".
Dabei gibst du dem Baustein also eine Zusatzinformation: die Anzahl der Wiederholungen, die ausgeführt werden sollen.
Die Schleife "weiß dann von selbst", wann sie fertig ist, ohne dass das Programm manuell gestoppt oder abgebrochen werden muss.
Diese Art der Wiederholung ist besonders sinnvoll, wenn dein Programm nach der Schleife weiterlaufen und andere Dinge erledigen soll.
Vielleicht soll dein Programm sogar die Ergebnisse aus einer Schleife in nachfolgenden Verarbeitungsschritten weiter nutzen können?

### Wie sagst du der Schleife, was sie wiederholen soll?
Das ist ganz leicht: du ziehst den zu wiederholenden Codeabschnitt in die Schleife hinein, sodass sie den Codeabschnitt umschließt.
Man nennt den von einer Wiederholung umschlossenen Code auch den "Schleifenkörper".
Du kannst beliebig viele Codeteile in eine Schleife einpacken.
Du kannst sogar Schleifen in Schleifen packen! Dies nennt man auch "Verschachtelung".


## Unterschiedlich reagieren
Ein Programm, egal wie groß oder klein, braucht die Möglichkeit auf unterschiedliche Situationen unterschiedlich zu reagieren.
Dazu muss es Entscheidungen treffen. Aber wie?

### Wenn...dann
Dafür gibt es den Baustein "wenn, ... dann". Man nennt diese Konstruktion auch "Fallunterscheidung".
Dabei gibst du dem Baustein eine Zusatzinformation: eine Bedingung.
Wenn die Bedingung eintritt, wird der Codeabschnitt ausgeführt, den dieser Baustein umschließt.
Wenn die Bedingung nicht eintritt, wird der Codeabschnitt übersprungen.
Da ein Programm von oben nach unten abgearbeitet wird, kannst du beliebig viele Fallunterscheidungen hintereinander durchführen lassen, um mehrere Bedingungen zu testen und daraufhin dein Programm unterschiedlich reagieren zu lassen.
Wenn keine zutrifft, werden alle übersprungen.
Mehrere Fallunterscheidungen zu machen wird auch "Verzweigung" genannt. Dabei stellt man sich die Äste eines Baums vor, die in unterschiedliche Richtungen führen können, wenn man sie mit dem Finger nachzeichnet.
Vielleicht hilft es dir auch, wenn du dir vorstellst, dass du deinem Programm die "Spielregeln" klar machst.


### Wie du eine Bedingung formulierst
Eine Bedingung ist eine Aussage, die mit "wahr" oder "falsch" beantwortet werden kann. Solche Aussagen sind meistens sehr kurz und simpel.
Dazu benötigst du einen Hilfsbaustein: Operatoren. Keine Bange, dabei handelt es sich nur um Vergleiche, die dein Programm verstehen und auswerten kann. Du wirst bestimmt merken, dass du die meisten Operatoren sogar schon kennst!
Hier sind zwei Beispiele für Bedingungen mit Operatoren:
1)farbe = blau
2)hund1 > hund2.
Die Operatoren sind also die Zeichen zwischen den Werten. Im ersten Beispiel ist der Operator das Gleichheitszeichen.
Weißt du, wie der Operator im zweiten Beispiel heißt? Woher kennst du diese Zeichen?

### Tipp: Deine Bedingung als Frage
Gedanklich kannst du eine Bedingung für dich als Frage übersetzen:
Ist der Wert in "farbe" blau?
Ist die gedrückte Taste die gesuchte Taste?

Sobald dein Progamm an dieser Stelle ankommt, prüft es die Aussage, d.h. es führt einen Wertevergleich mittels Operator durch. Kommt es zu dem Ergebnis "wahr", führt es den nachfolgenden Codeabschnitt aus.
Was passiert, wenn das Ergebnis des Vergleichs in einer Bedingung "falsch" ergibt?

### Wo hat die Bedingung ihren Platz?
Damit die Bedingung ihren Zweck erfüllen kann, muss sie am Anfang stehen und wird in das Feld nach dem "wenn" eingetragen.
Wenn du Vergleiche auswählst achte dabei auf die eckige Form des Bedingungs-Feldes in deinem Steuerbaustein - du kannst nur passende Elemente aus der Kategorie "Operatoren" hineinziehen.
Bedingungen kann man sogar kombinieren. Darüber erfährst du etwas im nächsten Absatz. Vorher solltest du die besprochenen Steuerbausteine in Scratch praktisch nachvollziehen, denn Programmieren bedeutet auch Dinge auszuprobieren und zu experimentieren.
Steuerelemente werden in Scratch in orange hervorgehoben.


### Komplexere Entscheidungen
Manchmal muss man erst mehrere Informationen sammlen und auswerten, um eine Entscheidung treffen zu können.
Deshalb kannst du deinem Programm mitteilen, dass mehrere Bedingungen gleichzeitig "wahr" sein müssen, um zu entscheiden, ob ein Codeabschnitt ausgeführt wird. Das heißt, dein Programm muss mehrere Vergleiche durchführen, bevor es etwas tun darf.
Dazu gibt es den Baustein "und": Zum Beispiel "farbe = blau" und "leertaste gedrückt".
Gedanklich kannst du es so übersetzen: Ist der Wert von "farbe" blau und ist **gleichzeitig** die Leertaste gedrückt? Gleichzeitig ist hierbei sehr wichtig!

Wie entscheidet dein Programm, wenn du den Baustein "nicht" oder "oder" benutzt?
Probier' es aus!


## Puh, Gedankenchaos?
Wenn du dir nicht sicher bist, wie dein Programm an einer kniffeligen Stelle verlaufen soll, hilft es Stift und Papier zur Hand zu nehmen und zu visualisieren:
Mit einem Diagramm kannst du deine Gedanken ordnen und erst einmal zeichnerisch Ideen ausprobieren. Dabei soll das vorgestellte Flussdiagramm ein Vorschlag sein:
**_<img von flussdiagramm>_**
An jeder Verzweigung stellst du gedanklich deine Frage.
Dann formulierst du sie als Bedingung mittles Operatoren für dein Programm um.
Anschließend überlegst du dir, was passieren soll, wenn die Frage mit "wahr" beantwortet wird.
Dann überlegst du dir, was passieren soll, wenn sie mit "falsch" beantwortet wird.
Die möglichen Wege für deinen Programmfluss zeichnest du als Zweig.
So kannst du dir deinen eigenen "Fahrplan" skizzieren.

Dein Diagramm muss nicht "formal richtig" sein! Du kannst es so verändern, wie es für dich am besten funktioniert.

## Mit Verzögerung reagieren
Zur Erinnerung: ein Programm wird von oben nach unten, Zeile für Zeile abgearbeitet. Es hat keinen Grund, Teile zu überspringen oder an einer Stelle absichtlich auf etwas zu warten, es sei denn du sagst es ihm. Man spricht auch davon, dass das Programm "pausiert". Wenn ein Program "hängt" ist das hingegen ein anderes Warten, als das wovon hier die Rede ist, das ist dann ein nicht gewolltes Warten.
Wann könnte es nutzen, dass ein Programm an einer Stelle pausiert, bevor es den nächsten Schritt ausführt?

### Wie lange warten?
In Scratch hast du zwei Möglichkeiten eine Pause einzubauen.
Die einfachste Pause, die du ausprobieren kannst, ist die mit einer festen Wartezeit.
Dazu bietet dir Scratch den Baustein "warte x Sekunden" an. Als Zusatzinformation gibst du eine Zahl als Wartezeit ein.
So garantierst du, dass an einer bestimmten Stelle in deinem Programm **immer** pausiert wird und die Pause **immer die gleiche Dauer** hat.
Oft weiß man zu Beginn noch nicht genau, wie lang eine Pause sein muss. Probiere verschiedene Werte aus!

### Flexiblere Pausen ...
Manchmal muss die Pause etwas länger oder etwas kürzer sein und man findet einfach keinen Wert, der passt!
Du hast die Möglichkeit "passgenaue" Pausen zu bestimmen. In Scratch heißt dieser Baustein "warte bis".
Zum Beispiel kannst du so lange warten, bis ein bestimmtes Ereignis stattgefunden hat.
Dazu brauchst du etwas, das du schon kennen gelernt hast: die Bedingung.
Anstelle einer Wartezeit bestimmst du nun also eine "Wartebedingung".

Mit deinem Wissen über Bedingungen, Operatoren und Ereignisse kannst du nun verschiedene Wartebedingungen ausprobieren.
Falls es dir noch schwer fällt, versuche die Fragetechnik auf Papier oder bei deinen Coaches.


## Klone
Oft leiht man sich Begriffe und Ideen aus anderen Wissenschaften, um Mechanismen/Programmierkonzepte anschaulicher zu bennen. Hier bedient man sich der Idee des "Klonens" aus der Biologie.
Sicher hast du schon einmal davon gehört: Ein Klon ist eine Kopie eines Lebewesens. Dieses Lebewesen ist aus exakt den gleichen Informationen wie das Original aufgebaut. Diese Idee lässt sich übertragen: In Scratch kannst du mehrere Lebewesen vom gleichen Bauplan zum Leben erwecken und sie individuell steuern. Der "Bauplan" könnte z.B. eine Grafik oder ein Lebewesen sein, das bereits existiert. Der Vorteil liegt darin, dass dein Computer nur einmal den Bauplan "laden" muss. Man nennt einen grafischen Bauplan auch "Spritesheet".

Um einen Klon zu erzeugen wählst du den Baustein "erzeuge Klon von" und gibst als Zusatzinformation deinen Bauplan mit.
Mit dem Baustein "wenn ich als Klon entstehe" kannst du der Kopie direkt sagen, wie sie sich verhalten soll, sobald sie auf dem Bildschirm erscheint. So weiß ein Klon direkt, was er zu tun hat.
Übrigens wird nicht nur das grafische Aussehen eines Originals kopiert, sondern auch seine Fähigkeiten, wie z.B. laufen oder springen. Diese Fähigkeiten nennt man auch "Scripte".

Denke daran, dass dein Computer begrenzte Ressourcen hat.
Was passiert, wenn du immer mehr Klone erstellst?
Dieses Problem müssen z.B. auch Spieleentwicklerinnen berücksichtigen.
Welchen Baustein könntest du nutzen, um die Menge der Klone unter Kontrolle zu halten?


## Weitere Bausteine
Ein paar Bausteine haben wir nicht im Detail besprochen, das macht aber nichts. Du musst nicht erst alles verstanden haben, bevor du anfangen kannst. Probiere aus, was passiert, wenn du z.B. "stoppe" auswählst. Wenn du es genauer wissen willst, lohnt sich ein Blick in die Dokumentation.
**_<Link>_**
