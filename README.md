# java-lerntagebuch
Dokumentation meines Lernfortschritts 

## Woche 1 (01.06.2026 bis 07.06.2026)

### Projektstart
- Projekt "Befindlichkeitsinterview" begonnen.
- Erste Konsolenausgabe erstellt.
- Benutzereingaben mit Scanner eingelesen.
- Erste String-Variable verwendet.

### Erste Ja/Nein-Abfragen
- if- und else-Anweisungen eingesetzt.
- Strings mit equals() verglichen.
- Problem mit Groß- und Kleinschreibung erkannt.
- equalsIgnoreCase() kennengelernt und eingebaut.

### GitHub
- Projekt auf GitHub veröffentlicht.
- Erste Commits erstellt.
- Änderungen aktualisiert und gepusht.
- Commit-Nachrichten geschrieben

### Skalenabfragen
- Skalen zur Befindlichkeitsabfrage eingebaut.
- int-Variablen verwendet.
- Wertebereich definiert (z.B. 1-10)

### Scanner-Probleme
- Problem zwischen nextInt() und nextLine() entdeckt.
- Verstanden, warum Eingaben übersprungen werden.
- Scanner-Verhalten besser kennengelernt.

### While-Schleifen
- Erste while-Schleife erstellt.
- Endlosschleife erzeugt.
- Entlosschleife analysiert und behoben.
- Wiederholte Eingabe ermöglicht.

### Eingabevalidierung
- Werte außerhalb des erlaubten Bereichs erkannt.
- Benutzer erneut nach gültigen Wert gefragt.
- Bereiche 1-10 und 1-100 überprüft.

### Prozentangaben
- Anspannungsskala erweitert.
- Eingabe zunächst als String verarbeitet.
- contains() kennengelernt.
- replace() kennengelernt.
- Prozentzeichen(%) entfernt.
- String in int umgewandelt.
- Integer.parseInt() verwendet.
- Prozentangaben wie "40%" akzeptiert.

### Logische Operatoren
- || (ODER) verwendet.
- && (UND) verwendet.
- ! (NICHT) verwendet.
- Fehler in einer While-Bedingung erkannt und behoben.

### Ja/Nein-Validierung
- Ungültige Texteingabe erkannt.
- Nur noch "ja" oder "nein" akzeptiert (Unabhängig von Groß-/Kleinschreibung).
- Wiederholte Abfrage bei ungültigen Eingaben eingebaut.

### Lerntagebuch
- Eigenes GitHub-Repository für das Lerntagebuch erstellt.
- README-Datei angelegt.
- Struktur für die Dokumentation des Lernfortschritts begonnen.

### Informationsblatt im Befindlichkeitsinterview optimiert
- Skill-Infoblatt überarbeitet
- Text auf Verständlichkeit geprüft
- Abschnitte klarer formuliert

### Gestaltung der Konsolenausgabe
- Auswertung optisch überarbeitet
- Überschriften und Abstände verbessert
- Informationen/Fakten übersichtlicher dargestellt
- Meldungen sichtbarer gestaltet

### Fehlermeldung mit try/catch
- try/catch kennengelernt
- NumberFormatException verwendet
- Benutzereingaben auf ungültige Zeichen gepprüft
- Bereichsprüfung und Fehlerbehandlung kombiniert

### Erkenntnisse
- Ein praktisches Projekt zu starten, unterstützt mein eigenständiges Lernen mehr als nur die reine Theorie.
- Kleine Komfortfunktionen benötigen oft überraschend viel Logik.
- Schleifen verstehe ich besser, wenn ich ein konkretes Problem lösen möchte.
- Fehler selbst zu finden kostet Zeit, führt aber zu nachhaltigem Verständnis.
- Das Programm muss nicht nur funktionieren, sondern auch verständlich sein.
- Gute Struktur verbessert die Lesbarkeit.
- Benutzerfreundlichkeit ist ein wichtiger Teil der Softwareentwicklung.
- Kleine optische Verbesserungen können die Wirkung des Programms deutlich verändern.


## Woche 2 (08.06.2026 bis 14.06.2026)

### Auswertung 
- Wertebereich für die Parameter (Schlafqualität/Stimmung/Anspannung) erstellt
- Gelernt wie eingegebene Daten mit if else Anweisung weiterverarbeitet werden können
- Eingaben strukturiert verarbeitet und übersichtlich gestaltet

### Gestaltung der Konsolenausgabe
- Auswertung der erhaltenen Fakten mit Harken und Kreuzsymbol erweitert

### Projektstart Fitness-Assistent
- Ein neues Projektkonzept geplant um Lerninhalte aus Woche 1 zu vertiefen
- Ein neues GitHub-Repository erstellt und veröffentlicht

### Wiederholte Lerninhalte im neuen Projekt
- If else Anweisungen geschrieben
- try/catch angewendet um Fehlermeldungen bei der Benutzereingabe abzufangen
- Benutzereingaben mit scanner einlesen (Datentyp String und Int)
- Eingabe als String eingelesen/Leerzeichen und Maßeinheiten via contains() und replace()ersetzt
- Gestalltung der Konsolenansicht
- Wertebereiche festgelegt und mittels if Anweisungen überprüft
- Werte verglichen mit kleiner, kleiner oder gleich,größer,größer oder gleich
- Boolische Operatoren verwendet (logisches Und + logisches Oder sowie bedingtes und + bedingtes oder)

### Datentyp Double verarbeitet
- Datentyp Double gearbeitet, um Dezimalzahlen korrekt zu verarbeiten
- Datentyp String in Double umgewandelt mit Double.parseDouble()
- Eingabevalidierung mit try/catch, falls Benutzer Komma statt Punkt eingibt
- Double Variable auf zwei Nachkommastellen gerundet mit System.out.printf(...%.2f%n, bmi)

### Berechnung angegebener Werte für den BMI
- Formel für die Berechnung des BMI recherchiert und in das Programm implementiert
- Auswertung für den BMI Wert männlich/weiblich/divers differenziert gestalltet um Körperzusammensetzung besser berücksichtigen zu können
- Tabelle zur Auswertung erstellt und Konsolenausgabe übersichtlicher gestaltet
- Mathematische Formeln zur Berechnung des BMI sowie der Wertebereiche (Untergewicht/Normalgewicht/Übergewicht/Adipositas) angewendet und gelernt diese strukturiert in Java zu verarbeiten

### Implementierung Grundumsatz in der Ausgabe
- Berechnung mithilfe der Mifflin-St.Jeor-Formel durchgeführt
- Differenzierung bei der Berechnung m/w/d berücksichtigt und Formel angepasst
- Ausgabe zu Informationen über Grundumsatz ermöglicht

### Erkenntnisse
- Programmierarbeit besteht nicht nur aus Code schreiben
- Ein Projekt bedarf Planung und der Überlegung, welche Daten benötigt werden
- Auch muss überlegt werden, wie die Benutzereingabe gestaltet werden soll um die Werte weiterverarbeiten zu können
- Es bedarf Wiederholung der Lerninhalte um diese weiter zu verinnerlichen
- Es gab einen Rundungsfehler den ich beheben konnte. Ein "kleines" Detail führte zu einer auffälligen Abweichung in der Ergebnisausgabe (25.0 statt 24.91 angegeben)
- Geschriebener Code wiederholt sich an vielen Stellen. Den Code kann ich kürzen indem ich Funktionen und Methoden anwenden (Themenbereiche die ich im nächsten Schritt lernen möchte)


## Woche 3 (15.06.2026 bis 21.06.2026)
### Wiederholte Lerninhalte im neuen Projekt
- If else Anweisungen geschrieben
- try/catch angewendet um Fehlermeldungen bei der Benutzereingabe abzufangen
- Benutzereingaben mit scanner einlesen (Datentyp String und Int)
- Eingabe als String eingelesen/Leerzeichen und Maßeinheiten via contains() und replace()ersetzt
- Gestalltung der Konsolenansicht
- Wertebereiche festgelegt und mittels if Anweisungen überprüft
- Werte verglichen mit kleiner, kleiner oder gleich,größer,größer oder gleich
- Boolische Operatoren verwendet (logisches Und + logisches Oder sowie bedingtes und + bedingtes oder)

### Projektstart Fitness-Assistent-Reworked
- Variablen wurden genauer benannt um sie einfacher weiterverarbeiten zu können
- Struktur des Programmcodes optimiert (Abfrage der Körpermesswerte/Interpretation/Auswertung/Methoden
- Erste Methoden implementiert
- BMI Interpretation abhänngig vom Alter berechnet
- Einordnung des angegebenen Alters in eine Altersgruppe
- try/catch Eingabevalidierung angewendet und Scannerposition korrigiert
- Formel zur Berechnung des Grundumsatz/Leistungsumsatz mithilfe des PAL-Wertes ermittelt/angewendet
- Formel zur Berechnung des Grundumsatzes/Leistungsumsatzes und Gesamtumsatzes implementiert und ausgewertet ausgegeben
- Makronährstoffverteilung (KH;E;F) anhand des Gesamtumsatzes berechnet und in der Auswertung mittels einer Methode ergänzt

### Methoden
- BMI Werte für die Wertetabelle anhand der festgestellten Altersgruppe berechnet
- Eingabevalidierung der Größe und des Gewichts mit einer Methode optimiert
- Programmteile im Eingabebereich als Methoden ausgelagert (Eingabe lesen/prüfen Größe,Gewicht,Alter,Geschlecht,Aktivitätslevel)
- Programmteile im Verarbeitungsteil als Methoden ausgelagert (Berechnung BMI,Altersgruppe,Grundumsatz,Leistungsumsatz,Gesamtumsatz)
- Programmteile zur Ausgabe der Auswertung als Methoden ausgelagert (Profil,BMI Tabelle,Energiebedarf)
- Angewendete Funktionen beinhalten sowohl einzelne als auch mehrere Parameter aber auch Funktionen ohne Rückgabewert

### Vergleichsoperatoren
- Zu den bereits angewendeten Operatoren(<,<=,>,>=) erfolgte im neuen Projekt die Durchführung eines Vergleichs mit dem Operator(==)

### Werte runden
- Zahlenwerte auf bestimmte Nachkommastelle mit Math.round gerundet
- Nachkommastelle vom Datentyp double nachträglich entfernt

### Erkenntnisse
- Ich habe diese Woche angefangen mich mit Methoden zu bewassen
- Ich habe verstanden, dass eine Methode einen Namen, Parameter und einen Rückgabewert besitzen kann
- Nicht jede Methode muss einen Wert zurückgeben (void)
- bestehende Programmteile meines Fitness-Assistenten habe ich in Methoden ausgelagert
- Lernziel: Ich möchte mich weiter mit der strukturierung meines Codes beschäftigen und werde dazu weitere Methoden verwenden um wiederkehrende Aufgaben auszulagern
- Ich habe Methoden angewendet um die main() übersichtlicher zu gestalten (Die main(9-Methode ist nun deutlich übersichtlicher geworden
- Ich habe Hilfsmethoden angewendet um die jeweiligen Methoden kürzer schreiben zu können (weniger Wiederholungen)
- Lernziel: Methoden im nächsten Schritt prüfen da immernoch vereinzelt Wiederholungen vorkommen
- Gedanke : ich glaube das die angewendeten Methoden zum Teil noch optimiert werden können
- Lernziel: Lerninhalte zum Themenbereich Funktionen wiederholen und Mithilfe des Buchs (Vorkurs Informatik für dummies) vertiefen.

## Woche 4 (22.06.2026 bis 28.06.2026)
### Methoden
- Hilfsmethode zur Prüfung des Wertebereichs PAL hinzugefügt und aus Methode lesePAL ausgelagert
- Hilfsmethode zur Prüfung des Wertebereichs der Altersspanne hinzugefügt und aus Methode leseAlter ausgelagert
- Hilfsmethode zur Prüfung des Wertebereichs zur Größe hinzugefügt und aus der Methode leseGroesse ausgelagert
- Methode zur Bestimmung des BMI Wertes zur Obergrenze entfernt und diese Berechnung zur Methode gibBMItabelleaus hinzugefügt

### Weitere Überprüfungen
- Schreibweise von Variablen und Methoden an die Java-Konventionen angeglichen (Kleinschreibung+Umlaute)

### Erkenntnisse
- Hilfmethoden hinzuzufügen verkürzt den Programmcode innerhalb der Methode und gestaltet diese Übersichtlicher
- Methoden erfüllen einen Zweck
- Themenbereich Methoden/Funktionen weiter bearbeiten

### Projektstart Skillchain
- Arrays als neues Thema gestartet
- Zum Lernen das Projekt Skillchain gestartet und in Eclips angelegt
- Überlegt welche Daten ein Skill besitzen soll (Name,Dauer der Anwendung,Skillwert)

### Wiederholungen der letzten Woche
- Anwenden von Methoden und Hilfsmethoden um den Programmcode übersichtlicher zu gestalten
- Schreibweise der Methoden und Variablen an Java-Konventionen angepasst
- Eingabevalidierung mit try/catch 
- Prüfung Wertebereich mit While-Schleife
- Vergleichsoperatoren angewendet
- Datentyp von String zu double verändert

### Erkenntnisse/Gedanken
- Ich wende im neuen Projekt Arrays an, möchte ich zu dem neuen Themenbereich die Objektorientierung als Thema hinzunehmen?
- Lernziel für nächste Woche: Arrays erzeugen, anwenden, Werte weiterverabreiten
- Projekt Skillchain fortsetzen

## Woche 5 (29.06.2026 bis 05.07.2026)
### Arrays
- Parallele Arrays werden über den gleichen Index miteinander verbunden. Die erleichtert die Weiterverarbeitung.
- erstellen einer for-Schleife um Skills gefiltert nach eingegebener Zeit sowie Kategorie auszugeben
- mit array.length bleibt die Schleife flexiebel, auch wenn ich nachträglich die Liste der Skills erweitern möchte
- Hilfsvariable wurde angewendet um jede Kategorie nur einmal ausgeben zu lassen. (Hilfsvariable war der "Start")

### Auswahlalgorithmus für Skillchain Version 1
- eine zweite for-Schleife verarbeitet anschließend ausschließlich die gefilterten Skills
- Algorithmus wählt aus jeder vorhandenen Kategorie einen Skill aus
- Algorithmus erweitert 

### Zwischenspeicherung gefilterter Skills mittels Hilfsvariable
- Einführung Hilfsvariable "anzahlPassenderSkills"
- Speicherung passender Skill-Indizes im Array "passende Skills"
- Mithilfe der Hilfsvariable "anzahlPassenderSkills" werden passende Skills fortlaufend gespeichert, ohne Lücken im Array zu erzeugen
  
### Skillchain erweitert
- Ausgabe der Anwendungsdauer jedes Skills ergänzt
- Ausgabe der Effektivität (1-5 Punkte) ergänzt

### Zeitbegrenzung vorbereitet
- Mithilfe einer Hilfsvariable wird die Skillchain jetzt auf die eingegebene Anwendungsdauer des Benutzers begrenzt
- Zeitprüfung in die zweite for-Schleife integriert

### Erkenntnisse
- parallele Arrays möchte ich durch Klasse Skill ersetzen
- Alle Eigenschaften des Skills gehören zusammen und können deshalb als Objekt zusammengefasst werden
- Umbau auf objektorientiertes Programmieren für die nächsten Arbeitseinheiten geplant
- Der Algorithmus funktioniert, ist aber noch nicht optimal

## Woche 6 (20.07.2026 bis 26.07.2026)
### Einstieg in die objektorientierte Programmierung (OOP)
- Erste Klasse "Skill" erstellt
- Eigenschaften eines Skills (Name, Kategorie,Dauer,Effektivität) als Attribute zusammengefasst
- Konstruktor erstellt, um neue Skill-Objekte zu erzeugen
- Verständnis entwickelt, dass eine Klasse eine "Bauanleitung" für Objekte darstellt

### Datenstrukturen verbessert
- Die bisherigen parallelen Arrays wurden durch ein Array "Skill" ersetzt
- Alle Eigenschaften eines Skills befinden sich nun in einem Objekt

### Methode angepasst
- Methode auf Objektorientierung umgestellt
- Zugriff erfolgt nun über Objektattribute statt über mehrere Arrays

### Fehlersuche
- Debug-Ausgabe zur Kontrolle von Parametern eingesetzt
- Fehler durch vertauschte Methodenparameter (stresslevel und zeit) gefunden und behoben

### Persönliche Erkenntnisse
- Eine Klasse beschreibt den Aufbau eines einzelnen Objekts
- Im Anschluss konnte ich mehrere Objekte erzeugen
- Das Umstellen eines bestehenden Arrays auf Objekte ist deutlich anspruchsvoller als eine reine Klasse zu erstellen
- Ich merke das ich die objektorientierte Denkweise noch üben/verinnerlichen muss
- Besonders das Umstellen bereits vorhandener Methoden fällt mir schwer

### nächste Schritte
- Objektorientierung weiter verinnerlichen und Code entsprechend anpassen
- Auswahl der SkillChain optimieren

### Methode in Klasse Skill
- erste Methode in die Klasse Skill verschoben
- Ausgabe von Name, Dauer und Effektivität innerhalb der Skillchain erfolgt jetzt über die Methode in der Klasse Skill 
  
