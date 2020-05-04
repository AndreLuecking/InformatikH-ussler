# Informatik Häussler

# Aufgabenstellung: Rechner für komplexe Zahlen
- Einlesen einer komplexen Zahl über die Konsole (Koeffizienten ODER Exponential-
Darstellung)
- Einlesen einer zweiten komplexen Zahl über die Konsole (Koeffizienten ODER Exponential-
Darstellung)
- Verarbeitung der beiden Zahlen (Grundrechenarten)
- Speicherung von Eingaben und Ergebnis als XML (Koeffizienten- UND Exponential-
Darstellung)
- Ausgabe des Ergebnisses über die Konsole (mit Nachfrage, ob Koeffizienten ODER
Exponential-Darstellung)

Anstöße:
- Empfohlene XML-Bibliothek: LibXml2 (via NuGet)
- Einlesen/Ausgabe und BL als Bibliotheken/Module des Hauptprogramms


# Aufgabestellung 2: Minesweeper
- Minenfeld-Größe und Minen-Anzahl über die Konsole einlesen
- Zufällige Verteilung der Minen über das Spielfeld
- Koordinaten der angelegten Minen als CSV abspeichern (%d-%d; erst Rechts-, dann
Hochwert-Achse)
- Ausgabe des Blankofeldes nach folgendem Prinzip (Beispiel für 10x10): siehe PDF
- Einlesen der „Feld-Klicks“ über die Kommandozeile:
o „%d-%d“ für einen Linksklick (Feld aufdecken)
o „#%d-%d“ für einen Rechtsklick (Fahne setzen)
- Verarbeitung der Eingabe und Ausgabe von
o Zahl („1“-„8“)
o Null-Feld („.“)
o Fahne („#“)
o Mine („*“)
- Bei Klick auf ein Feld ohne Minen alle benachbarten Null-Felder aufdecken
- Bei Klick auf eine Mine die Ausgabe wie folgt aktualisieren:
o Alle Minen-Felder mit Minen („*“) versehen
o Die Meldung „You lose“ anzeigen
- Wenn alle Nicht-Minen-Felder aufgedeckt sind, die Ausgabe wie folgt aktualisieren:
o Minenfelder mit Fahnen („#“) versehen
o Die Meldung „You win“ anzeigen

Anstöße:
- Einlesen/Ausgabe und BL als Bibliotheken/Module des Hauptprogramms
- Laufzeit-Effizienz des Herzstücks (nach Klick auf ein Feld) beachten, verschiedene Konzepte
evaluieren
