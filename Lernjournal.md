# Lernjournal 

## Lernsession 1

Wichtige kommanden:

``` bash

git init -b main # Repo erstellen
git add . # Alle Dateien zum Stating Area einfügen
git status # Prüfen, ob die Dateien verfolgt sind
git commit -m "..." # Einen Schnappschuss des Repo erstellen
```

## Lersession 2

**Lernspur und Übergabepunkt sichern**

* Was ist der Unterschied zwischen Git und GitHub?

Git sist ein Versionskontrollesystem und GitHub ist eine Online-Platform, wo ich mein Projekt herunterladen kann und kooperieren.

* Welcher Git-Schritt ist für dich bereits sicher?

Ich kann sicher einen Ablauf durch führen, wo ich: 
	1. ein Git Repo erstelle
	2. Änderungen mache
	3. geänderte Dateien zum Staging-Bereich hinzufüge
	4. commit erstelle
	5. einen neuen Zweig erstelle
	6. diesen Zweig mit dem Hauptzweig zusammenführe
	7. Zurück mithilfe von "reset" gehe

* Wo stehst du im Microsoft-Learn-Modul Einführung in GitHub?

Vor dem Übung.

* Was ist dein nächster konkreter Schritt in Lernsession 03?

Als nächstes werde ich in Lernsession 03 einen GitHub-Flow erstellen.

**Exit-Ticket**

1. git commit -m "First"

2. "Feature" branch - ist der Zweig, wo ich etwas bearbeite und, nachdem es fertig ist, mit "main" Zweig zusammenführe.

3. Welche workflow sollen wir für den bevorstehenden Projekt benutzen.

## Lernsession 3

In GitHub können wir das Repo steuern:

![GitHub Tabs](<img/Screenshot 2026-10-12 091330.png>)

Diese Tabs helfen uns, die Einstellungen ändern und verschiedene Operationen mit unserem Repo ausführen. 

Für Beispiel, kann man:
* Pull Requests ansehen, zulassen oder ablehnen (Pull Requests)
* Probleme mit unserem Projekt ansehen, beantworten und erledigen (Issues)

## Lernsession 4 

Wenn es einen Problem gibt, das wir als Informatiker lösen müssen, hilft es, jedes Teil zu isolieren:
* Problem
* Ziel
* Lösung

Wichtig ist, beim Erstellen von den Zielen, Kriterien testbar zu machen. Wir müssen klar verstehen, wann der Kriterium erfüllt ist.

Anstatt: "Das Programm muss richtig funktionieren", sollte man schreiben:
* Es gibt keine Fehler oder Abstürze.
* Während dem Testen, der Zielpersonal soll keine Fragen stellen müssen.

```
Abstrakter Ablauf des Programms

1. Summe zu 0 einsetzen.
2. Artikelname eingeben
3. Einzelpreis eingeben
4. Menge eingeben
5. Menge mit Einzelpreis multiplizieren, zur Summe addieren.
6. Den Benutzer fragen, ob nächsten Artikel einzugeben.
7. Wenn ja, zum Schritt 2 gehen. Wenn nein, weitergehen.
8. Die Liste von Artikel formatiert ausgeben, die Summe ausgeben.

Überprüfung:
1. summe ist 0.
2. Apfelschörle eingeben
3. 2.50 eingeben
4. 3 eingeben
5. 2.50 * 3 = 7.50, 0 + 7.50 = 7.50, summe = 7.50
6. "Ja" eingeben
2. Sandwich eingeben
3. 5.80 eingeben
4. 2 eingeben
5. 5.80 * 2 = 11.60, 7.50 + 11.60 = 19.10, summe = 19.10
6. "Nein" eingeben
7. Weitergehen
8. Liste und Summe ausgeben.
```

