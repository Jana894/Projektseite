<h1 id="Projektseite">

<h1 id="kapitel3">3. Projektseite</h1>
  
### Inhaltsverzeichnis
<li><a href="#kapitel3.1">Programme</a></h2></li>
<li><a href="#kapitel3.2">Idee</a></h2></li>
<li><a href="#kapitel3.3">Ergebnis</a></h2></li>
<li><a href="#kapitel3.4">Fazit</a></h2></li>
  
<h2 id="kapitel3.1">Programme</h2>

![logo snap](Bilder/logo_snap.png "Logo Snap")

Für unser Projekt haben wir "Snap!" genutzt, da dieses Programm gerade für Anfänger sehr gut geeignet und einfach zu verstehen ist. Bei "Snap!" wird keine "Programmiersprache" genutzt, sondern Bausteine, auf denen in Englisch steht, was passieren soll, wenn sie zusammengesetzt werden. Für Anfänger ist gerade dies von Vorteil, da man sich nicht erst in die "Programmiersprache" einarbeiten muss, sondern direkt anfangen kann und die Herausforderung "nur" ist, die Bausteine richtig zu kombinieren, um den gewünschten Befehl auszuführen. Wir mussten feststellen, dass es trotz dieser Vereinfacherung gar nicht so einfach ist, immer die richtigen Blöcke zukombinieren, um das gewünschte Ergebnis zu erzielen, jedoch haben wir immer eine Lösung gefunden und konnten weiterarbeiten und unsere Ideen umsetzten.


![logo pixilart](Bilder/logo_pixilart.webp "Logo Pixilart")

Für die äußere Gestaltung haben wir uns mit dem Pixelzeichner "pixilart" beschäftigt und sind mit diesem sehr gut zurecht gekommen. Es handelt sich bei diesem Pixelzeichner um einen kostenlosen Onlinezeichner, der sehr einfach zu verstehen ist, weshalb wir schnell und ohne große Einarbeitung erste Ergebnisse erzielen konnten.

![logo FL-Studio](Bilder/FL_Studio_Logo.jpg "Logo FL-Studio")

Für die Musik in unserem 2D-Spiel hat Bente sich zusammen mit ihrem Bruder mit "FL-Studio" beschäftigt. FL-Studio ist eine "Digital Audio Workstation", was bedeutet, dass Audiosignale erzeugt und bearbeitet werden können. Hauptsächlich wird diese "Workstation" für die Musikproduktion, das Mixing und Mastering von Musik verwendet.

<h2 id="kapitel3.2">Idee</h2>
Unsere Grundidee basiert auf einem "Jump and Run"-Spiel, in welchem eine Figur in mehreren Leveln Hindernisse überwinden und zum Ziel gelangen muss. Hierbei ist es uns wichtig, dass die Figur weder von unten durch die Hindernisse hindurch darauf springen kann, noch von einem Hindernis zum nächsten Hindrnis in der Luft laufen kann. Es muss also eine Schwerkraft oder Gravitationskraft erstellt werden, genauso wie undurchdringbare Hindernisse.

<details id="Link"><summary>verworfene Ideen</summary>
  
- 2D-Spiel: Labyrinth -> Tierpaare müssen sich gegenseitig finden 

- 2D-Spiel: Irrgarten -> farbige Kugel müssen durch ein Wirrwarr von Wegen den richtigen Weg in das Rohr ihrer eigenen Farbe finden
</details>

<h2 id="kapitel3.3">Ergebnis</h2>
Unser 2D-Spiel ist ein "Jump and Run"-Spiel mit vier verschiedenen Leveln geworden. Pro Level kommt ein neues Element hinzu, welches das Level anspruchsvoller und spannnender gestalten soll.
So ist im ersten Level das Ziel, die Zielflagge zu erreichen, in dem man von Hindernis zu Hindernis springt, was im ersten Moment noch nicht allzu schwierig erscheint. Im zweiten Level dann, haben wir noch ein Feuer eingebaut, in welchem die Figur "verbrennt", sobald sie es berührt und das Level von vorne beginnen muss. Im dritten Level ist das Ziel zwei Münzen einzusammeln, wobei wir drei Münzen eingebaut haben, damit man mehrere Kombinationsmöglichkeiten hat. Sind die zwei Münzen eingesammelt ist das Level geschafft und man wird weiter geleitet. Im vierten und letzten Level dann, muss die Figur über Mauern springen, um ans Ziel zu gelangen, wobei wir auch hier ein Feuer eingebaut haben, welches die Figur, sobald sie es brührt, zwingt von vorne zu beginnen.
Das Thema unseres 2D-Spiels ist "Dschungel", Level 1 bis 3 stellen hierbei den Dschungel mit Lianen und viel grün dar und Level 4 das Ende des Dschungels, da schon erste Mauern zu finden sind und auf den Felsen (Ebenen) nur noch ein bisschen Moos wächst und keine Lianen mehr hängen.

<details id="Link"><summary>Erklärung Ergebnis</summary>

<details id="Link"><summary>Erklärung Figur</summary>

Unsere Figur bewegt sich, indem man sie mit den Tasten "a", "d" und "w" steuert. Mit der "d"-Taste geht die Figur nach vorne, mit der "a"-Taste wieder zurück und drückt man die "w"-Taste, springt unsere Figur, dabei ist "15" die Höhe und Geschwindigkeit, die unsere Figur springt bzw "-15" die, die sie fällt. Die Variable "sprung an" signalisiert userer Figur, dass sie nun springen muss. Am Anfang jedes Levels muss man die "space"-Taste drücken, damit sich die Figur auf ihre festgelegte Startposition begibt, welche sich bei x: -206 y:-122 befindet.

![Figur](Bilder/Bewegungen_der_Figur.png "Figur")
</details>

<details id="Link"><summary>Erklärung Musik</summary>

Die Musik in unserem Spiel haben Bente und ihr Bruder mithilfe von "FL-Studio" erstellt. Wenn unser Spiel beginnt, fängt zunächst der "Startsound" an sich abzuspielen, wählt man nun ein Level aus und klickt den "Levelbutton", wir "play-Gamesound" vom jeweiligen "Levelbutton" gebroadcastet und der Sound wechselt zum "Gamesound". Erreicht man nun in den einzelnen Level das Ziel, wechselt der Sound wieder zum "Startsound" mit dem Wechsel zur "Stage" mit dem "zurück zur Levelauswahl"-Button und ein neuer Broadcast signalisiert den Wechsel. Dieser Broadcast ist der selbe, wie der, der die einzelnen Level beendet (Erklärung siehe "Erklärung Level 1").
Um beide Sounds gut hören zu können, muss die Lautstärke auf dem jeweiligen Gerät auf circa 50 gestellt werden, da der "Start-Sound" lauter als der "Game-Sound" ist, damit man sich während der einzelnen Level besser konzentrieren kann.
  
![Musik](Bilder/Programmierung_Musik.png "Musik")

![Levelbutton](Bilder/Programmierung_Levelbutton_II.png "Levelbutton")
</details>

<details id="Link"><summary>Erklärung allgemeine Befehle</summary>

Für den Startbildschirm, welcher den Beginn unseres 2D-Spiels darstellt, haben wir zunächst ein eigenes "Stage Costume" erstellt und danach eigene "Blocks", welche die einzelnen "Sprites" der jeweiligen "Stage Costumes" "hiden" oder "shown", wobei für den Startbildschirm alles "gehidet" werden muss außer das was zum Startbildschirm dazugehört. Klickt man nun den Startknopf wird "StartGame" gebroadcastet, was zum Wechsel zum "Costume" "Levelauswahl" führt, wo erneut alle Elemente außer die "gehidet" werden müssen, welche für diesen Bildschirm wichtig sind. 
Nachdem man ein Level beendet hat, gelangt man zum "Stage Costume" "Level ... geschafft", wo ebenfalls durch einen "Knopf" ein Broadcast verbreitet wird ("zurück zur Levelauswahl"), welcher das "Stage Costume" zurück in das der Levelauswahl ändert.
Wir haben auch noch einen Pop-up programmiert, der zu Beginn jedes Levels erscheint und dem Spieler mitteilt, dass die "space"-Taste gedrückt werden muss, damit die Figur erscheint und man das Spiel spielen kann. Hierfür wird die "Sprite" "gehidet", wenn man das Spiel beginnt bzw. die "space"-Taste gedrückt wird. Die "Sprite wird "geshowed", wenn der Broadcast zum Starten eines Levels gebroadcastet wird.
  
![allgemeine Befehle](Bilder/Programmierung_allgemeiner_Befehle.png "allgemeine Befehle")

![Startknopf](Bilder/Programmierung_Startknopf.png "Startknopf")

![zurück zur Levelauswahl](Bilder/Programmierung_zurück-zur-Levelauswahl.png "zurück zur Levelauswahl")

![Pop up](Bilder/Programmierung_Pop-up.png "Pop up")
</details>

<details id="Link"><summary>Erklärung Level 1</summary>

Um Level 1 zu starten, muss zunächst der Levelbutton 1 geklickt werden, welcher daraufhin "Start-Level-1" broadcastet und zum "Stage Costume" Level 1 wechselt. Hier kommen dann wieder unsere "Blocks" zum Einsatz, die alles "hiden", was nicht zum Level 1.1 gehört. Durch das Bewegen der Figur (siehe Erklärung Figur) gelangt man von Hindernis zu Hindernis und sobald man Ebene 3 erreicht, wird "Switch-to-Level 1.2" gebroadcastet und das "Stage Costume" wird zu Level 1.2 geändert und nun alle Elemente "gehidet", die nicht zum Level 1.2 gehören. Berührt die Figur nun die Zielflagge, wird "Ziel-erreicht" gebroadcastet und das "Costume" zu "Level-1-geschafft" geändert. Von dort gelangt man zurück zur Levelauswahl und kann die nächsten Level spielen (siehe Erklärung allgemeine Befehle).
  
![Levelbutton](Bilder/Programmierung_Levelbutton_I.png "Levelbutton")
  
![Level 1](Bilder/Programmierung_Level1_I.png "Level 1")

![Level 1](Bilder/Programmierung_Level1_II.png "Level 1")
</details>

<details id="Link"><summary>Erklärung Level 2</summary>

Das Grundprinzip ist in jedem Level gleich, jedoch kommt in Level 2 das neue Element "Feuer" hinzu. Wenn die Figur das Feuer berührt, wird "restart" gebroadcastet und das Level startet von vorne, die Figur wird als an ihren Startpunkt x: -210 y: -122 zurückgesetzt. Wird Ebene 8 berührt, wird "Switch-to-Level 2.2" gebroadcastet und das "Stage Costume" ändert sich von Level 2 zu Level 2.2. Auch dieses Level endet mit Berühren der Zielflagge, wodurch "Ziel-erreicht-2" gebroadcastet wird und man zum "Stage Costume" "Level-2-geschafft" gelangt, von wo es zurück zur Levelauswahl geht (siehe Erklärung Level 1).

![Levelbutton](Bilder/Programmierung_Levelbutton_III.png "Levelbutton")

![Level 2](Bilder/Programmierung_Level2_I.png "Level 2")

![Level 2](Bilder/Programmierung_Level2_II.png "Level 2")
</details>

<details id="Link"><summary>Erklärung Level 3</summary>

Auch in diesem Level bleibt das Grundprinzip bestehen, jedoch gibt es zwei neue Aspekte, die dieses Level von den anderen unterscheiden. Zum Einen, dass die Figur in diesem Level Münzen einsammeln muss, wobei jenachdem, um welche Münze es sich handelt, "Münze [...] einsammeln" gebroadcastet wird, wodurch die Münze die Information bekommt, sich zu "hiden". Zum Anderen endet dieses Level nich mit Berühren der Zielflagge, sondern wenn genau zwei Münzen eingesammelt wurden, wofür wir eine neue Variable "Anzahl-Münzen" erstellt haben. Wenn diese "Anzahl-Münzen" dann genau zwei ist, wird "Ziel-erreicht-3" gebroadcastet und ab dort ist der Ablauf dann exakt der gleiche, wie in Level 1 und 2.

![Levelbutton](Bilder/Programmierung_Levelbutton_IV.png "Levelbutton")

![Level 3](Bilder/Programmierung_Level3_I.png "Level 3")

![Level 3](Bilder/Programmierung_Level3_II.png "Level 3")

![Münzen](Bilder/Programmierung_Münzen.png "Münzen")
</details>

<details id="Link"><summary>Erklärung Level 4</summary>

In unserem letzten Level haben wir erneut ein Feuer eingebaut, bei welchem sich die Programmierung jedoch nicht verändert hat (siehe Erklärung Level 2). Neu hinzu ist das Element "Mauer" gekommen, durch welche die Figur nicht hindurch laufen kann, sondern drüber springen muss. Berührt unsere Figur Ebene 26 und Ebene 30 werden "Switch-to-Level 4.2" und "Switch-to-Level 4.3" gebroadcastet und die "Stage Costumes" wechseln von Level 4 zu Level 4.2 und dann zu Level 4.3. In diesem Level gibt es wieder eine Zielflagge, und wenn unsere Figur diese berührt, wird "Ziel-erreicht-4" gebroadcastet und man gelangt wie schon in den vorherigen Leveln zurück zur Levelauswahl.

![Levelbutton](Bilder/Programmierung_Levelbutton_V.png "Levelbutton")

![Level 4](Bilder/Programmierung_Level4_I.png "Level 4")

![Level 4](Bilder/Programmierung_Level4_II.png "Level 4")
</details>
</details>

<h2 id="kapitel3.4">Fazit</h2>
Am Ende dieses sehr zeitaufwändigen und umfangreichen Projekts, können wir sagen, dass es trotz vieler Schwierigkeiten und so einigen Problemen, für die wir zum Glück alle eine Lösung gefunden haben, sehr viel Spaß gemacht hat, etwas Eigenes zu programmieren und am Ende dann auch ein Ergebnis vor Augen zu haben, mit dem wir sehr zufrieden sind. Denn dafür, dass wir beide vorher noch nie etwas programmiert haben, geschweige denn Vorkenntnisse hatten, sind wir sehr stolz darauf, dass wir unser eigenes 2D-Spiel programmiert haben und doch mehr umsetzen konnten, als wir uns am Anfang zugetraut haben.
Unserer Meinung nach war der Informatikunterricht immer eine schöne Abwechslung zum Frontalunterricht, den man die restliche Woche über hat. Am Anfang war es zwar schwer, ganz ohne Imput und konkrete Vorgaben etwas zu finden, was man machen könnte, jedoch sind wir im Nachhinein froh darüber, dass wir unser eigenen Kreativität freien Lauf lassen konnten und tatsächlich überwiegend eigenständig arbeiten konnten. 
