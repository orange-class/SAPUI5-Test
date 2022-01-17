# SAPUI5-Test

## Herunterladen des Projekts
1. Rechtsklicke auf Workspace > Git > Clone Repository

2. Folgende URL muss dort eingetragen werden: https://github.com/Medsmiley/SAPUI5-Test.git
3. Klicke nun auf "Clone".


## Begrifflichkeiten
An dieser Stelle bitte einmal die git_guidelines.md lesen. 
Diese erklären einige wichtige Begrifflichkeiten.

Kurz:
- Fetch = Mit der online Version vergleichen: gibt es Änderungen?
- Pull = Änderungen herunterladen in die lokale Version
- Commit = Eigene Änderungen zu einem Thema in Paketen zusammenfassen und kommentieren 
- Push = Alle Commits in den Online-Speicher hochladen
- Pull Request = Verschmelzen mit der Original-/Master-/Live-Version einfordern



## Aufgabe

Damit ihr den ganzen Zyklus einmal umsetzen könnt, werdet ihr jetzt euren Namen in das Dokument mit den Autoren eintragen und online stellen.

1. Klicke auf "Pull" und hole dir alle neuen Änderungen. Das sollte IMMER gemacht werden, bevor du deine eigene Kopie abspalten willst!
2. Klicke auf das Plus hinter "Branch" in der Git-Oberfläche in der SAP WEB IDE.
3. Der Base-Branch muss main sein. "Base" bedeutet, dass du dir diesen einmal kopierst. Dieser soll also auf main basieren, denn du weißt nicht, was andere in ihrem Branch machen und der main ist die aktuellste Version. Deshalb erstellst du eine Kopie von main. 
4. Gib ein: "beispiel/name" (exakt so, name = euer Name ohne Umlaute). Das ist nun der neue Name der Kopie! Nun klicke auf "OK". Du befindest dich nun automatisch im neuen Branch.

5. Öffne diese Datei hier und scrolle nach unten bis zur Namensliste.
6. Ändere das "O" hinter deinem Namen zu einem "X" und speichere die Datei.

7. In der Git-Oberfläche ist diese Änderung nun in der Liste aufgetaucht. 
8. Sieh zu, dass in der Spalte "Stage" ein Haken bei "ReadMe.md" drin ist.
(Alles mit Haken wird im Commit zusammengefasst -> somit kann man genau festlegen, was alles die gleiche Beschreibung bekommt)
8. Gib unten in der "Commit Description" die kurze knackige Beschreibung wie gelernt ein, z.B.: "UPDATE: mein Name"
9. Optional: gib einen kurzen Beschreibungstext ein. In dieser Oberfläche geht das beides nur zusammen in ein Feld :(

10. Klicke rechts auf "Commit". Alle markierten Änderungen wurden nun mit dieser Beschreibung in ein Änderungspaket zusammen gefasst.
11. Klicke auf "Push". Damit werden alle deine Änderungspakete hochgeladen.

12. Klicke nun auf der rechten Seite im weißen Bereich auf die blaue Fläche "Create Pull Request". Du wirst auf die Website weitergeleitet.
13. Ändere den Namen zu "Autor hinzufügen".
14. Schreibe in den Kommentar, dass du du als neues Mitglied nun deinen Namen der Autoren.txt hinzugefügt hast.
15. Wähle rechts bei "Reviewers" mind. 2 Mitglieder des Lore-Teams aus, z.B. DDeckert, Medsmiley, miafy oder MineSchokokeks.
Dadurch werden diese sogar eine E-Mail mit der Aufforderung erhalten, sich das anzusehen.
16. Darunter, bei "Assignees" wähle dich selbst aus.
17. Bei "Labels" wähle "Allgemein".
18. Klicke auf "Projects" und wähle "Allgemein".
Das packt diese Request automatisch in die Aufgabenliste des Projekts.
19. Klicke auf den großen grünen Button "Create Pull Request". 
Nun ist die Anfrage eingegangen. Wenn mindestens 2 Leute sie sich angesehen und bestätigt (approved) haben, wird deine Änderung zum master hinzugefügt und offiziell.

13. Zurück im Programm: Klicke in der Programm-Befehlszeile auf "Branch -> Delete". 
Sollte eine Frage auftauchen: Auf gar keinen Fall den Haken setzen um auch den Branch online zu löschen, sonst wird das mit der Request problematisch. 
Online wird der Branch automatisch gelöscht, wenn er in den master gemerged wurde. 
"Delete"


Person     Check
- Zobhan   X
- Devran   X
- Hua      X
- Nils     O
- Ismail   O
- Emerzon  O
- Lennart  X
- Käthe    X


## Weiterhin

Während deiner Arbeit am Projekt solltest du am Besten jedes Mal, wenn du aufhörst, deine Commits pushen. 
Damit ist ab dann jeder, der mit dir zusammen im gleichen Branch arbeitet auf dem aktuellen Stand. 
Beziehungsweise solltest du unerwartet ausfallen, hast du zumindest alles, was du getan hast, online gestellt und jemand anderes kann daran anknüpfen. 
Bevor du nicht gepusht hast, ist es nicht online!


## Falscher Branch!?!?!
Hast du versehentlich mit deiner Arbeit im falschen Branch begonnen (zB im Master), so ist das unkompliziert **SOLANGE NOCH KEIN COMMIT ERFOLGTE**. 
In dem Fall wartet viel Arbeit auf mich... 
Ansonsten kannst du einfach einen neuen Branch erstellen und wirst dann danach gefragt, ob du die bisherigen Änderungen mitnehmen oder auf dem Master/falschen Branch belassen möchtest.

Auf dem Master kannst du übrigens auch nicht pushen. Also nichts von deinen Änderungen online stellen. 


## Viel Spaß beim Arbeiten!