# Lernguide – Introduction to Computer Science

**Autor der Originalfassung:** Claudiu Dangulea · FH Wien der WKW  
**Originalstand:** 17. November 2026  
**Format:** korrigierte Markdown-Fassung auf Basis der Word-Datei

## Inhaltsübersicht

- [Hinweise zur KI-Nutzung](#hinweise-zur-ki-nutzung)
- [Grundlagen 1 – Geschichte der Informatik](#grundlagen-1-geschichte-der-informatik)
- [Grundlagen 2 – Hardware und Software (Wiederholung)](#grundlagen-2-hardware-und-software-wiederholung)
- [Grundlagen 3 – Zahlensysteme und Datendarstellung](#grundlagen-3-zahlensysteme-und-datendarstellung)
- [Grundlagen 4 – Algorithmen](#grundlagen-4-algorithmen)
- [Grundlagen 5 – Weitere Grundbegriffe (CS Unplugged)](#grundlagen-5-weitere-grundbegriffe-cs-unplugged)
- [Kapitel 1 – Welcome to the World of Digitalization](#kapitel-1-welcome-to-the-world-of-digitalization)
- [Kapitel 2 – What Exactly Is a Business Information System (BIS)?](#kapitel-2-what-exactly-is-a-business-information-system-bis)
- [Kapitel 3 – Data Management and Business Analytics](#kapitel-3-data-management-and-business-analytics)
- [Kapitel 4 – Automation](#kapitel-4-automation)
- [Kapitel 5 – Artificial Intelligence (AI)](#kapitel-5-artificial-intelligence-ai)
- [Kapitel 6 – Cybercrime and Cybersecurity](#kapitel-6-cybercrime-and-cybersecurity)
- [Kapitel 7 – Digital Compliance and Corporate Digital Responsibility (CDR)](#kapitel-7-digital-compliance-and-corporate-digital-responsibility-cdr)
- [Kapitel 8 – Digitalization Projects](#kapitel-8-digitalization-projects)
- [Quellenverzeichnis](#quellenverzeichnis)

---

> **Hinweis zur überarbeiteten Fassung (17. November 2026):** Grundlage ist der von Claudiu Dangulea mit Claude erstellte Lernguide. Diese Markdown-Fassung wurde mit ChatGPT (OpenAI) aus der Word-Datei übertragen und in ausgewählten sachlichen Punkten korrigiert. Die ursprüngliche KI-Nutzungserklärung dokumentiert die Erstellung der Word-Originalfassung; die unten ergänzten Quellen belegen einzelne Änderungen. Eine vollständige Validierung aller Aussagen anhand sämtlicher Lehrunterlagen ist damit nicht verbunden.

# Über diesen Lernguide

## Aufbau

Der Lernguide hat zwei Teile: fünf Grundlagenkapitel der Informatik (Geschichte, Hardware und Software, Zahlensysteme und Datendarstellung, Algorithmen, weitere Grundbegriffe) und die acht Kapitel des Study Guide „Digitalizing Organizations“ (STAGES), jeweils mit Abschnitten, Unterthemen und Definitionen. Kapitel 1–8 folgen der Gliederung des Study Guide; englische Fachbegriffe sind beibehalten, damit sie mit den Prüfungsunterlagen übereinstimmen.

Herkunftsangaben in Klammern, etwa „(CS Unplugged)“ oder „(Study Guide, Kapitel 2)“, verweisen auf das Quellenverzeichnis am Ende. „(Ergänzung)“ kennzeichnet Inhalte aus allgemeinem Fachwissen, die in keiner der genannten Quellen stehen. Öffentlich erreichbare Quellen sind dort verlinkt. Stand: 17. November 2026.

# Hinweise zur KI-Nutzung

Dieser Lernguide ist mit Unterstützung eines KI-Systems entstanden. Die folgenden Angaben legen offen, wofür die KI eingesetzt wurde und wo ihre Grenzen liegen.

- **Werkzeug:** Claude, Modell Claude Opus 5.5 (Anthropic), eingesetzt am 17. November 2026 in der Claude-App mit Zugriff auf die Kursunterlagen des Verfassers.

- **Vorgaben des Verfassers:** Aufgabenstellung, Auswahl der Kursunterlagen, Gliederung nach Kapiteln, Abschnitten und Unterthemen, Themenwünsche (Geschichte der Informatik, Hardware/Software, Zahlensysteme, Algorithmen), Nachvollziehbarkeit für Dritte und die Word-Vorlage stammen von Claudiu Dangulea.

- **Von der KI erledigt:**
  - Kursunterlagen gelesen und ausgewertet, vor allem den Study Guide zu Kapitel 1–8, CS Unplugged und Unterlagen zur CS50-Vorlesung „Algorithms“.
  - Inhalte gegliedert, zusammengefasst und ins Deutsche übertragen.
  - Themen, die in den Unterlagen fehlen oder nur angerissen werden (u. a. Geschichte der Informatik, Rechnerarchitektur, Hexadezimal- und Oktalsystem), aus allgemeinem Fachwissen ergänzt und mit „(Ergänzung)“ gekennzeichnet.
  - Jahreszahlen der Zeittafel sowie öffentlich erreichbare Quellen und Rechtstexte per Websuche ermittelt und im Quellenverzeichnis verlinkt.
  - Einen öffentlichen Übungsfragenkatalog (GitHub) mit dem Study Guide abgeglichen.
  - Den Text in diese Word-Vorlage übertragen.

- **Grenzen:** KI-Zusammenfassungen können verkürzen, falsch gewichten oder Fehler enthalten. Der Lernguide ersetzt den Study Guide nicht. Die rechtlichen Angaben in Kapitel 7 geben den Stand des Study Guide wieder und sind keine Rechtsberatung.

- **Verantwortung:** Die inhaltliche Prüfung und die Verantwortung für die Verwendung liegen beim Verfasser.

# Grundlagen 1 – Geschichte der Informatik

Die Informatik wächst aus drei Strängen zusammen: mechanischen Rechenmaschinen, der Lochkarten-Datenverarbeitung und der Theorie der Berechenbarkeit. Die Jahreszahlen der Zeittafel stammen überwiegend aus der Chronologie von lernhelfer.de, einzelne aus CS Unplugged und dem Skriptum von Pomberger.

## Begriff

- Informatik: Wissenschaft von der systematischen, automatischen Verarbeitung von Information mit Computern (Ergänzung). CS Unplugged beschreibt sie als Fachgebiet, das erforscht, wie Computer funktionieren und wie man schnelle, leicht bedienbare Software schreibt.

- Teilgebiete (Ergänzung): theoretische Informatik (Automaten, Berechenbarkeit, Komplexität), technische Informatik (Hardware), praktische Informatik (Algorithmen, Programmierung, Betriebssysteme), angewandte Informatik (z. B. Wirtschaftsinformatik).

## Zeittafel

| Jahr        | Ereignis                                                                      | Bedeutung                           |
|-------------|-------------------------------------------------------------------------------|-------------------------------------|
| um 1623     | Schickard baut die erste Rechenmaschine                                       | Mechanisches Rechnen                |
| 1644        | Pascal: erste erhaltene Maschine für Addition und Subtraktion                 | Mechanisches Rechnen                |
| 1673 / 1703 | Leibniz: Vier-Spezies-Rechenmaschine; 1703 Abhandlung über das Binärsystem    | Grundlage der Binärdarstellung      |
| 1822        | Babbage demonstriert ein kleines Versuchsmodell seiner Difference Engine; die vollständige Maschine wird damals nicht fertiggestellt | Mechanische Berechnung mathematischer Tabellen |
| 1890        | Hollerith-Lochkartenmaschine bei der US-Volkszählung; 1896 Firma, ab 1924 IBM | Maschinelle Datenverarbeitung       |
| 1936/37     | Turing und Post definieren Berechenbarkeit                                    | Beginn der theoretischen Informatik |
| 1938 / 1941 | Zuse: Z1 mit Gleitkomma, Z3 in Betrieb                                        | Programmgesteuerter Digitalrechner  |
| 1944/45     | Von Neumann: ein Speicher für Programm und Daten; Merge Sort                  | Von-Neumann-Architektur             |
| 1947        | Eine Motte wird im Relais des Harvard Mark II gefunden                        | Berühmter „Computer Bug“; der technische Begriff „Bug“ war bereits vorher gebräuchlich |
| 1946        | ENIAC (Röhrenrechner) geht in Betrieb                                         | Elektronischer Großrechner          |
| 1948        | Shannon: Information in Bits, Entropie                                        | Informationstheorie                 |
| 1950        | Turing: „Computing Machinery and Intelligence“, Turing-Test                   | Beginn der KI-Debatte               |
| 1947        | Erster funktionsfähiger Transistor bei Bell Labs                              | Grundlage für den späteren Ersatz vieler Elektronenröhren |
| ab 1965     | Integrierte Schaltkreise (Chips)                                              | Miniaturisierung                    |
| 1966        | ELIZA (Weizenbaum)                                                            | Frühes Sprachprogramm               |
| um 1971     | Hochintegrierte Chips; Intel 4004 als erster Mikroprozessor (Ergänzung)       | Prozessor auf einem Chip            |
| 1970er      | Lempel-Ziv-Kompression                                                        | Basis von ZIP, GIF, PNG             |
| 1976 / 1977 | Apple I (1976) und Apple II (1977); frühe Personal Computer existierten auch von anderen Herstellern | Verbreitung des Personal Computers |

Shannons Jahr 1948 ist eine Ergänzung; CS Unplugged nennt Shannon ohne Jahr. Die Datierungen zu Difference Engine, Motte, Transistor und Apple wurden anhand zusätzlicher historischer Quellen präzisiert (siehe Quellenverzeichnis).

## Begriffe aus der Geschichte

- Lochkarte: Datenträger, auf dem Löcher Zahlen und Buchstaben codieren; bis in die 1960er Standard der Datenverarbeitung.

- Relais → Röhre → Transistor → integrierter Schaltkreis → Mikroprozessor: die Bauteil-Generationen, jede kleiner, schneller und billiger als die vorige (Ergänzung).

- Stored Program (speicherprogrammiert): Programmanweisungen und Daten liegen im adressierbaren Speicher. Dadurch können Programme flexibel geladen und – unter entsprechenden Voraussetzungen – auch selbst verändert werden. Verzweigungen sind jedoch nicht ausschließlich auf diese Architektur beschränkt.

- Berechenbarkeit: Was sich überhaupt durch einen Algorithmus lösen lässt; formalisiert durch die Turingmaschine (Ergänzung).

# Grundlagen 2 – Hardware und Software (Wiederholung)

Hardware ist die physische Ausstattung, Software sind die Programme, die ihr sagen, was sie tun soll (Study Guide, Kapitel 2). Der Study Guide beschreibt Hardware und Software aus Sicht eines Business Information Systems; Rechnerarchitektur und Speicherhierarchie sind ergänzt.

## Grundprinzipien

- EVA-Prinzip (Ergänzung): Eingabe → Verarbeitung → Ausgabe, dazu Speicherung.

- Von-Neumann-Architektur (Ergänzung): Rechenwerk (ALU) und Steuerwerk bilden die CPU; dazu Arbeitsspeicher für Programm und Daten, Ein-/Ausgabeeinheiten und ein Bussystem, das alles verbindet.

- Bit-Breite: Ein 32-Bit-Computer verarbeitet 32-Bit-Zahlen in einer Operation, ein 16-Bit-Computer braucht dafür zwei (CS Unplugged).

## Speicher und Datenträger

- Wie Bits physisch gespeichert werden: Transistor an/aus oder Kondensator geladen/entladen (Arbeitsspeicher), magnetische Ausrichtung (Festplatte), spiegelnd/nicht spiegelnd (CD, DVD) (CS Unplugged).

- RAM: sehr schnell, aber flüchtig – ohne Strom sind die Daten weg; teurer und kleiner als dauerhafter Speicher (Kapitel 3, In-Memory-Datenbank).

- Speicherhierarchie (Ergänzung): Register → Cache → RAM → SSD/Festplatte; je näher an der CPU, desto schneller, kleiner und teurer.

## Hardware-Kategorien im BIS

| Kategorie                  | Aufgabe                               | Beispiele                                 |
|----------------------------|---------------------------------------|-------------------------------------------|
| End User Devices           | Zugang zum System                     | Desktop, Laptop                           |
| Data Input Devices         | Erfassen realer Daten                 | Barcode-Scanner, RFID-Leser               |
| Output & Display Devices   | Anzeigen, Drucken                     | Monitor, Drucker                          |
| Network Devices            | Geräte verbinden                      | Router, Switch                            |
| Processing Devices         | Anwendungen ausführen                 | Server, GPU-Server                        |
| Storage Devices            | Daten aufbewahren                     | NAS, SAN                                  |
| Communication Devices      | Sprache und Video                     | Webcam, VoIP-Telefon                      |
| Security Devices           | Unerwünschten Zugriff abwehren        | Firewall                                  |
| Power Protection Devices   | Kurze Stromausfälle überbrücken       | USV, Akku                                 |
| Industrial Control Devices | Maschinen steuern                     | SPS (PLC), HMI                            |
| Production Devices         | Digitale Anweisung → physische Arbeit | Industrieroboter, CNC                     |
| Transaction Devices        | Zahlungen abwickeln                   | Kassensystem, Kartenterminal              |
| Logistics Devices          | Waren bewegen                         | Fahrerlose Transportfahrzeuge, Förderband |

## Software-Arten

- Systemsoftware: steuert die Grundfunktionen des Computers (Betriebssystem, Sicherheits- und Hilfsprogramme). Anwendungssoftware: erfüllt eine konkrete Aufgabe für den Nutzer.

- Sieben Kategorien (Kapitel 2): Betriebssystem (Windows, macOS, Linux), Produktivität (Office), Business Applications (ERP, CRM, SCM), Kommunikation & Kollaboration (Outlook, Zoom, Slack), Datenbankmanagement (MySQL, Oracle), Sicherheit & Utilities (Antivirus, Backup), Entwicklung (VS Code, GitHub).

- Programm: Liste von Anweisungen für eine bestimmte Aufgabe; Programmiersprache: Sprache mit begrenztem Befehlsvorrat, die der Computer wörtlich ausführt (CS Unplugged).

- Compiler übersetzt das ganze Programm vorab in Maschinencode, Interpreter führt es Anweisung für Anweisung aus (Ergänzung).

- Firmware: fest im Gerät gespeicherte Steuersoftware (Ergänzung).

## Cloud-Servicemodelle (Kapitel 1)

- IaaS: Server und Speicher mieten.

- PaaS: Entwicklungs- und Betriebsumgebung ohne eigene Serververwaltung.

- SaaS: fertige Software im Browser.

- Serverless: Code in der Cloud ausführen und nur die tatsächliche Rechenzeit bezahlen.

# Grundlagen 3 – Zahlensysteme und Datendarstellung

Computer stellen alles – Zahlen, Text, Bilder – mit nur zwei Zuständen dar, 0 und 1. Binärzahlen, Bilder, Kompression und Fehlererkennung stammen aus CS Unplugged (Teil I), Hexadezimal, Oktal und Umrechnung sind ergänzt.

## Stellenwertsysteme

| System                  | Basis | Ziffern  | Beispiel für 255 |
|-------------------------|-------|----------|------------------|
| Dezimal                 | 10    | 0–9      | 255              |
| Binär (Dualsystem)      | 2     | 0, 1     | 1111 1111        |
| Oktal (Ergänzung)       | 8     | 0–7      | 377              |
| Hexadezimal (Ergänzung) | 16    | 0–9, A–F | FF               |

- Stellenwert: Jede Stelle ist eine Potenz der Basis. Binär 10011 = 16 + 2 + 1 = 19.

- Binärkarten-Übung (CS Unplugged): Karten mit 1, 2, 4, 8, 16 Punkten; jede Zahl von 0 bis 31 hat genau eine Darstellung, die größte ist 31 (alle Karten offen). Jede weitere Karte verdoppelt den Bereich.

- Dezimal → binär (Ergänzung): fortlaufend durch 2 teilen, die Reste von unten nach oben lesen. 13 → 6 R1 → 3 R0 → 1 R1 → 0 R1 = 1101.

- Binär → hexadezimal (Ergänzung): je 4 Bit sind eine Hex-Ziffer (1111 = F), je 3 Bit eine Oktalziffer.

## Einheiten

- Bit: eine 0 oder 1, die kleinste Informationseinheit.

- Byte: 8 Bit, darstellbar sind 0 bis 255.

- Mit n Bit lassen sich 2ⁿ verschiedene Werte darstellen (Ergänzung).

- Präfixe (Ergänzung): Kilobyte = 1000 Byte (dezimal), Kibibyte = 1024 Byte (binär).

## Text

- Zeichencodierung: Jedem Zeichen wird eine Zahl zugeordnet, die binär gespeichert wird (Geheimnachrichten-Übung: A = 1, B = 2 …).

- ASCII: verbreitete Codierung für lateinische Schrift; Schriften mit mehr Zeichen brauchen Codierungen mit mehr Bits pro Zeichen (CS Unplugged). Diese Rolle hat heute Unicode, etwa als UTF-8 (Ergänzung).

## Bilder

- Pixel: Bildpunkt; ein Schwarz-Weiß-Bild ist eine Folge von 0 und 1 pro Pixel (Faxgerät: ca. 1000 × 2000 Pixel).

- Lauflängencodierung: Statt jedes Pixel einzeln zu speichern, wird gezählt, wie viele gleiche Pixel aufeinander folgen. Faxe schrumpfen so auf etwa ein Siebtel.

- Farbbilder (Ergänzung): je Pixel Werte für Rot, Grün und Blau (RGB), meist 8 Bit pro Kanal.

## Kompression

- Ziel: weniger Speicherplatz und schnellere Übertragung, ohne mehr Hardware.

- Lempel-Ziv (LZ): verweist auf frühere Vorkommen gleicher Textstücke; Grundlage von ZIP, GIF, PNG; halbiert Text leicht.

- Häufige Zeichen bekommen kürzere Codes (Prinzip des Morsecodes).

- Grenze: Eine Nachricht lässt sich nicht unter ihre Entropie komprimieren (siehe Grundlagen 5).

## Fehlererkennung und -korrektur

- Paritätsbit: Zusatzbit, das die Anzahl der Einsen gerade macht. Mit Paritätsbits je Zeile und Spalte lässt sich ein einzelner Fehler nicht nur erkennen, sondern auch orten und korrigieren.

- Prüfziffer: letzte Ziffer, die aus den übrigen berechnet wird, etwa bei ISBN, Barcodes und Kontonummern.

- Fehlererkennung stellt fest, dass Daten beschädigt sind; Fehlerkorrektur rekonstruiert die Originaldaten.

## Datentypen (Kapitel 3)

Boolean (wahr/falsch), Integer (ganze Zahl), Float (Kommazahl), Date/Time, String (Text), Image, Audio & Video, Object (mehrere zusammengehörige Werte).

# Grundlagen 4 – Algorithmen

Ein Algorithmus ist eine Schritt-für-Schritt-Anleitung, die einem Computer sagt, wie er ein Problem löst (Glossar Kapitel 1). Quellen sind CS Unplugged (Teil II), die CS50-Vorlesung „Algorithms“ der Harvard University (2023) und das Skriptum „Algorithmen und Datenstrukturen“ von Pomberger (JKU Linz).

## Begriff und Eigenschaften

- Eigenschaften (Ergänzung): endlich beschrieben, eindeutig, ausführbar, terminiert nach endlich vielen Schritten.

- Darstellung (Ergänzung): Pseudocode, Flussdiagramm (Programmablaufplan), Struktogramm, Programmcode.

- Datenobjekt mit Schlüssel: Beim Sortieren werden Sätze nach einem Schlüsselattribut geordnet; struct bündelt zusammengehörige Felder, damit sie gemeinsam bewegt werden (CS50, Pomberger).

## Suchen

- Suchbegriff: das, wonach gesucht wird (Wort, Barcode, Name).

- Lineare Suche: ein Element nach dem anderen; schlechtester Fall n Schritte, bester 1.

- Binäre Suche: nur auf sortierten Daten; prüft die Mitte und halbiert den Bereich. Höchstens ⌊log₂n⌋ + 1 Schritte; 10.000 Produkte in 14 Schritten.

- Hashing: Aus dem Suchbegriff wird direkt die Speicherposition berechnet; meist sofort am Ziel. Kollision: zwei Schlüssel führen zur selben Position.

- Zielkonflikt: Binäre Suche ist schnell, setzt aber Sortieren voraus, das selbst Zeit kostet.

## Sortieren

| Verfahren      | Prinzip                                                    | Laufzeit                                                 | Stabil |
|----------------|------------------------------------------------------------|----------------------------------------------------------|--------|
| Selection Sort | Minimum im Rest suchen, nach vorne tauschen                | Θ(n²), n(n−1)/2 Vergleiche                               | Nein   |
| Bubble Sort    | Nachbarn vergleichen und tauschen                          | O(n²); Ω(n) nur mit Abbruch, wenn nichts getauscht wurde | Ja     |
| Insertion Sort | Element an die richtige Stelle im sortierten Teil einfügen | Fast linear bei vorsortierten Daten                      | Ja     |
| Merge Sort     | Halbieren, beide Hälften sortieren, zusammenmischen        | Θ(n log n); Zusatzspeicher n                             | Ja     |
| Quicksort      | Nach Pivot aufteilen, Teile rekursiv sortieren             | Im Durchschnitt O(n log n), Worst Case O(n²); oft schnell in der Praxis       | Nein   |
| Bucket Sort    | Verteilen nach bekanntem, kleinem Wertebereich             | Unter geeigneten Annahmen O(n + k), mit k Buckets; kein Vergleichssortieren                           | –      |

- Stabil: Elemente mit gleichem Schlüssel behalten ihre Reihenfolge.

- Für vergleichsbasiertes Sortieren gilt im Worst Case eine asymptotische Untergrenze von Ω(n log n).

- Zum Anschauen: [Sorting Algorithms Animations](https://www.toptal.com/developers/sorting-algorithms) und [Comparison Sorting Visualization](https://www.cs.usfca.edu/~galles/visualization/ComparisonSort.html).

## Rekursion und Teile-und-Herrsche

- Rekursion: Eine Funktion löst ein Problem, indem sie sich für ein kleineres Teilproblem selbst aufruft.

- Rekursionsanker: nicht-rekursiver Fall, der die Kette beendet; ohne ihn entsteht Endlosrekursion.

- Laufzeitkeller (Stack): Jeder Aufruf legt Parameter und lokale Variablen ab; zu tiefe Rekursion führt zum Absturz.

- Endrekursion: Nach dem rekursiven Aufruf folgt keine Berechnung mehr; nur sie lässt sich direkt in eine Schleife umwandeln (Fakultät ist es nicht, ggT nach Euklid schon).

- Teile und herrsche: Problem teilen, Teile lösen, Ergebnisse zusammensetzen (Merge Sort, Quicksort).

## Laufzeit und Komplexität

- O (höchstens), Ω (mindestens), Θ (genau) sind Wachstumsschranken; welcher Fall betrachtet wird (best, worst, average), ist eine eigene Frage.

- Konstanten fallen weg. Hintereinander ausgeführte Teile: Maximum. Verschachtelte Teile: Produkt (zwei Schleifen über n = n²).

- Polynomial (n², n³ …) vs. exponentiell (2ⁿ): Für große n ist jeder polynomielle Algorithmus schneller als ein exponentieller (CS Unplugged).

- Brute Force: alle Möglichkeiten durchprobieren; wächst meist exponentiell.

## Parallelität und Graphen

- Sortiernetzwerk: Mehrere Vergleiche laufen gleichzeitig; das Sechs-Zahlen-Netz braucht 12 Vergleiche, aber nur 5 Zeitschritte. Nicht jede Aufgabe lässt sich parallelisieren.

- Graph: Knoten und Kanten, die Beziehungen darstellen (nicht zu verwechseln mit einem Diagramm).

- Minimaler Spannbaum: verbindet alle Punkte mit minimaler Gesamtlänge; ein gieriger (greedy) Algorithmus findet ihn effizient.

# Grundlagen 5 – Weitere Grundbegriffe (CS Unplugged)

Die übrigen Teile von CS Unplugged führen in Informationstheorie, Netzwerke, Automaten, schwere Probleme, Kryptographie und Mensch-Computer-Interaktion ein. Weiterführendes zur theoretischen Informatik nennt das Quellenverzeichnis.

## Informationstheorie

- Information in Bit: Jede Ja/Nein-Antwort entspricht einem Bit (Claude Shannon).

- Informationsgehalt hängt davon ab, was man schon weiß: Unwahrscheinliches trägt mehr Information.

- Entropie: Informationsgehalt einer Nachricht; hängt von der Zahl der möglichen Ergebnisse und ihren Wahrscheinlichkeiten ab. Ein fairer Münzwurf = 1 Bit, eine gezinkte Münze weniger.

- Entscheidungsbaum: Folge von Ja/Nein-Fragen, die zur Antwort führt („Zwanzig Fragen“).

## Netzwerke

- Routing: den Weg einer Nachricht durch ein Netz bestimmen.

- Stillstand (Deadlock): Alle warten aufeinander, niemand kommt weiter. Gleichzeitig geänderte Daten müssen während des Updates gesperrt werden.

- Paket: Daten plus Header (Paketnummer, Anzahl, Bestätigung); Pakete können verloren gehen oder ihre Reihenfolge verlieren.

- Protokoll: Regeln und Zusatzinformationen, die eine zuverlässige Übertragung sichern, etwa TCP und UDP.

## Endliche Automaten und Programmiersprachen

- Endlicher Automat: Modell mit endlich vielen Zuständen; jede Eingabe führt in einen nächsten Zustand (Telefonmenü, Bankomat).

- Programmiersprache: eingeschränktes Vokabular von Anweisungen, die der Computer exakt ausführt – auch wenn das Ergebnis unsinnig ist.

- Bug: Programmfehler; Debugging ist das Finden und Beheben.

## Schwere Probleme (Hartnäckigkeit)

- Kartenfärbung: Mindestzahl an Farben, damit benachbarte Flächen verschieden sind; Vier-Farben-Vermutung 1852, bewiesen 1976.

- Dominierende Menge („Eiswagen“): möglichst wenige Knoten markieren, sodass jeder Knoten höchstens einen Schritt entfernt ist.

- Steinerbaum: wie der minimale Spannbaum, aber mit zusätzlichen Punkten; dadurch viel schwerer.

- Bei manchen **präzise definierten Entscheidungsvarianten** dieser Probleme ist kein Polynomialzeit-Algorithmus bekannt; solche Varianten können NP-vollständig sein (Ergänzung). Das gilt nicht pauschal für alle genannten Aufgaben: Planare Karten lassen sich beispielsweise mit höchstens vier Farben färben; die Frage nach einer 3-Färbung ist dagegen deutlich schwieriger. Die Aussage „NP-vollständig“ bezieht sich auf ein konkretes Entscheidungsproblem, nicht automatisch auf jede Formulierung einer Optimierungsaufgabe.

## Kryptographie

- Ziel: sicher und privat kommunizieren und kontrollieren, was andere über einen erfahren.

- Geheimnisse teilen: gemeinsam etwas berechnen (Durchschnittsalter), ohne Einzelwerte preiszugeben.

- Kryptographisches Protokoll: faire Entscheidung zwischen Parteien, die einander nicht trauen (Münzwurf übers Telefon).

- Public-Key-Verschlüsselung: Der öffentliche Schlüssel („Vorhängeschloss“) verschlüsselt, nur der private Schlüssel entschlüsselt; Grundlage von SSL/TLS.

- Authentifizierung: nachweisen, dass eine Nachricht wirklich vom angegebenen Absender kommt.

## Mensch und Computer

- Mensch-Computer-Interaktion: Systeme so gestalten, bewerten und umsetzen, dass Menschen produktiv und sicher arbeiten. Viele „menschliche Fehler“ sind Gestaltungsfehler.

- Turing-Test (1950): Ein Fragesteller kommuniziert per Fernschreiber mit Mensch und Computer; kann er sie nicht zuverlässig unterscheiden, gilt der Test als bestanden. Er misst Verhaltensäquivalenz, nicht Bewusstsein.

- ELIZA (1966): frühes Dialogprogramm, das ein Gespräch mit einfachen Mustern vortäuscht.

# Kapitel 1 – Welcome to the World of Digitalization

Fünf Abschnitte: die drei Stufen der Digitalisierung, zehn digitale Geschäftsmodelle, 15 Trends, vier Wurzeltechnologien und ein Glossar für Manager.

## 1.1 Digitization, Digitalization, Digital Transformation

1.  Digitization: Papier wird zur Datei (Rechnung scannen und als PDF speichern).

2.  Digitalization: Ein Papierprozess wird durch einen Softwareprozess ersetzt (Rechnung im Billing-System erstellen und mailen).

3.  Digital Transformation: Das ganze Unternehmen wird verändert, digitale Prozesse werden Kern des Geschäftsmodells (Onlineshop als Herz des Händlers).

## 1.2 Digital Business Models

Ein digitales Geschäftsmodell nutzt digitale Technologien, Daten und Online-Netzwerke als zentrale Elemente, um Kunden zu bedienen und Geld zu verdienen – im Gegensatz zu physischen Assets und Offline-Prozessen.

| Modell            | Definition                                                                   | Einnahme                                        | Beispiele                 |
|-------------------|------------------------------------------------------------------------------|-------------------------------------------------|---------------------------|
| E-Commerce        | Waren oder Dienste online verkaufen                                          | Kaufpreis plus Liefergebühr                     | Amazon, Etsy, Zalando     |
| Subscription      | Wiederkehrende Gebühr für laufenden Zugang                                   | Monatliche oder jährliche Zahlung               | Netflix, Spotify Premium  |
| Freemium          | Basisversion gratis für alle                                                 | Premiumfunktionen, mehr Inhalte, weniger Limits | Spotify, Canva, Dropbox   |
| Advertising       | Werbeplätze an Zielgruppe verkaufen                                          | Nach Einblendungen oder Reaktionen              | Google Ads, Meta Ads      |
| Marketplace       | Plattform verbindet unabhängige Verkäufer und Käufer, besitzt die Ware nicht | Provision pro Transaktion                       | Airbnb, Uber              |
| SaaS              | Anbieter hostet Software, Zugriff über das Internet                          | Abo je Plan                                     | Microsoft 365, Salesforce |
| Pay per Use       | Zahlung je verbrauchter Einheit                                              | Gebühr je gemessener Nutzung                    | AWS Lambda, Zipcar        |
| Affiliate         | Kunden an andere Unternehmen vermitteln                                      | Provision für getrackte Vermittlung             | Amazon Associates         |
| Licensing         | Nutzung geistigen Eigentums erlauben                                         | Lizenzgebühr und Royalties                      | Arm, Dolby                |
| Data Monetization | Rechtmäßig erhobene, anonymisierte Daten als Insight-Produkt                 | Abo oder Projektgebühr                          | Experian, NielsenIQ       |

## 1.3 Current Digitalization Trends

| Trend                                 | Definition                                                                                                            |
|---------------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Automation und RPA                    | Software, Hardware und AI übernehmen Routinearbeit; RPA = Software-Bots, die menschliche Bildschirmaktionen nachahmen |
| Generative AI                         | Erzeugt neue Texte, Bilder, Audio, Video; Ergebnis muss geprüft werden                                                |
| AI Agents                             | Verfolgen ein Ziel über mehrere Schritte, planen und nutzen Werkzeuge selbst                                          |
| Business Intelligence                 | Geschäftsdaten analysieren und als entscheidungsrelevante Information aufbereiten                                     |
| Digital Customer Experience Platforms | Kundeninteraktionen über Website, App, Social Media und Filiale verbinden                                             |
| Remote Work Technologies              | Videokonferenz, geteilte Dokumente, Cloud-Ablage für ortsunabhängige Arbeit                                           |
| Sustainable Digital Solutions         | Digitale Werkzeuge senken Umweltwirkung; der Nutzen muss an real eingesparten Ressourcen gemessen werden              |
| Cybersecurity                         | Schutz von Systemen und Daten; Zero Trust = jeder Nutzer und jedes Gerät wird vor dem Zugriff geprüft                 |
| Cloud First Operations                | Cloud als bevorzugter Betriebsweg, aber nicht zwingend für jedes System                                               |
| 5G Connectivity                       | Mobilfunk mit hoher Datenrate, geringer Verzögerung, vielen Geräten                                                   |
| Low Code / No Code                    | Anwendungen mit visuellen Bausteinen statt Programmcode bauen                                                         |
| Edge Computing                        | Daten nahe am Entstehungsort verarbeiten, wenn Verzögerung teuer oder gefährlich wäre                                 |
| AIOps                                 | AI für den IT-Betrieb: Auffälligkeiten erkennen, Ausfälle vorhersagen, Routine automatisieren                         |
| Digital Twins                         | Laufend aktualisiertes digitales Abbild eines Objekts, Systems oder Prozesses                                         |
| Quantum Computing                     | Nutzt Quantenphysik für bestimmte Probleme; für die meisten Geschäftszwecke noch im Entstehen                         |

## 1.4 The Four Root Technologies

- Internet of Things: verbindet physische Objekte mit entfernten Computern; Geräte melden Zustände und führen Befehle aus, in Echtzeit, periodisch, ereignisgesteuert oder verzögert.

- Cloud Computing: Rechenleistung eines Anbieters als Service; Kapazität wächst und schrumpft nach Bedarf, Abrechnung nach Abo oder Nutzung.

- Big Data: Datenmengen, die Tabellenkalkulation und Standarddatenbanken überfordern. Volume (Menge), Velocity (Tempo neuer Daten), Variety (Formenvielfalt).

- Artificial Intelligence: Software, die aus Beispielen trainiert wurde und Muster auf neue Daten anwendet.

- Entstehung: Ziel festlegen → historische Beispiele sammeln → richtige Antwort zuordnen → trainieren → testen und verbessern → einsetzen und überwachen.

- Typen: Recognition, Predictive, Recommendation, Optimization, Generative, Conversational, Agentic.

## 1.5 Digitalization Terms Every Modern Manager Needs to Know

| Bereich           | Begriff                                            | Definition                                                                                                    |
|-------------------|----------------------------------------------------|---------------------------------------------------------------------------------------------------------------|
| Infrastruktur     | API                                                | Digitaler Bote, über den Softwaresysteme automatisch Informationen austauschen                                |
| Infrastruktur     | Cloud Computing                                    | Programme und Daten auf Internet-Servern statt auf eigener Hardware                                           |
| Infrastruktur     | Edge Computing                                     | Daten nahe am Entstehungsort verarbeiten                                                                      |
| Infrastruktur     | IoT                                                | Alltagsobjekte mit Internetverbindung, die selbst Daten senden                                                |
| Infrastruktur     | 5G                                                 | Schnellste Mobilfunktechnik für viele vernetzte Geräte                                                        |
| Infrastruktur     | SaaS / PaaS / IaaS                                 | Software im Browser / Entwicklungsumgebung ohne Serververwaltung / Server und Speicher mieten                 |
| Infrastruktur     | Serverless Computing                               | Anwendungen ohne Serververwaltung; bezahlt wird nur die genutzte Rechenzeit                                   |
| Infrastruktur     | Microservices                                      | Große Anwendung in kleine, unabhängig aktualisierbare Teile zerlegt                                           |
| Infrastruktur     | Server                                             | Leistungsstarker Rechner, der anderen Computern Dienste bereitstellt                                          |
| Infrastruktur     | Legacy System                                      | Älteres System, noch in Betrieb, schwer mit Neuem zu verbinden                                                |
| Infrastruktur     | Scalability                                        | Fähigkeit, mehr Last oder Wachstum effizient zu bewältigen                                                    |
| Sicherheit        | Cybersecurity                                      | Schutz von Computern, Netzen und Daten vor Angriffen                                                          |
| Sicherheit        | Firewall                                           | Kontrolliert, welche Daten ins Netz hinein- oder hinausdürfen                                                 |
| Sicherheit        | VPN                                                | Verschlüsselter Tunnel für die Internetverbindung                                                             |
| Sicherheit        | Blockchain                                         | Auf viele Rechner verteiltes, praktisch unveränderbares Transaktionsregister                                  |
| Sicherheit        | Biometrics                                         | Identifikation über Fingerabdruck, Gesicht oder Stimme                                                        |
| Daten             | Big Data                                           | Riesige Datenmengen, die Spezialwerkzeuge brauchen                                                            |
| Daten             | Data Analytics                                     | Daten auf Muster und Trends untersuchen                                                                       |
| Daten             | Business Intelligence                              | Werkzeuge und Prozesse, die Rohdaten in Entscheidungswissen verwandeln                                        |
| Daten             | Predictive Analytics                               | Mit historischen Daten und Statistik künftige Entwicklungen vorhersagen                                       |
| Daten             | Data Mining                                        | Verborgene Muster in großen Datenbeständen finden                                                             |
| Daten             | Data Warehouse                                     | Zentraler Speicher für strukturierte Daten aus vielen Quellen, für Analyse                                    |
| Daten             | Data Lake                                          | Speicher für Rohdaten im Originalformat                                                                       |
| Daten             | KPI                                                | Messbare Kennzahl für den Fortschritt zu wichtigen Zielen                                                     |
| Daten             | Dashboard                                          | Visuelle Anzeige der wichtigsten Kennzahlen in Echtzeit                                                       |
| Daten             | Data Visualization                                 | Daten als Diagramme, Grafiken, Karten darstellen                                                              |
| AI                | Artificial Intelligence                            | Systeme, die Aufgaben lösen, die sonst menschliche Intelligenz brauchen                                       |
| AI                | Machine Learning                                   | AI, die aus Datenmustern Vorhersagen oder Entscheidungen lernt                                                |
| AI                | Deep Learning                                      | Machine Learning mit neuronalen Netzen für komplexe Muster                                                    |
| AI                | Neural Network                                     | Vom Gehirn inspiriertes System aus verbundenen Knoten                                                         |
| AI                | Supervised / Unsupervised Learning                 | Lernen mit bekannten richtigen Antworten / Muster ohne Vorgaben finden                                        |
| AI                | NLP                                                | Computer verstehen, interpretieren und erzeugen menschliche Sprache                                           |
| AI                | Algorithm                                          | Schritt-für-Schritt-Anleitung zur Lösung eines Problems                                                       |
| AI                | Chatbot / Voice Assistant                          | Programm für Text- bzw. Sprachdialoge                                                                         |
| AI                | AI Agent                                           | Führt komplexe Aufgaben selbstständig aus und trifft Entscheidungen                                           |
| Geschäftssoftware | ERP                                                | Integriertes System für alle Kernprozesse (Finanzen, Produktion, HR)                                          |
| Geschäftssoftware | CRM                                                | Kundeninteraktionen und Verkaufschancen über den Kundenlebenszyklus verwalten                                 |
| Geschäftssoftware | SCM                                                | Material-, Waren-, Informations- und Geldfluss vom Lieferanten zum Kunden koordinieren                        |
| Geschäftssoftware | CMS                                                | Webinhalte ohne Programmierkenntnisse erstellen und verwalten                                                 |
| Automatisierung   | Automation                                         | Aufgaben mit minimalem menschlichem Eingriff erledigen                                                        |
| Automatisierung   | Business Process Automation                        | Komplexe Geschäftsabläufe automatisch ausführen                                                               |
| Automatisierung   | RPA                                                | Software-Roboter für repetitive, regelbasierte Bildschirmarbeit                                               |
| Methoden          | Agile                                              | Arbeit in kleinen, häufigen Iterationen mit laufendem Feedback                                                |
| Methoden          | DevOps                                             | Entwicklung und IT-Betrieb verbinden für schnellere, verlässliche Auslieferung                                |
| Methoden          | Use Case                                           | Szenario, wie ein Nutzer mit einem System ein Ziel erreicht                                                   |
| Methoden          | User Story                                         | Kurzbeschreibung einer Funktion aus Nutzersicht („Als … möchte ich …, damit …“)                               |
| Methoden          | UX / UI                                            | Wie sich die Nutzung anfühlt / sichtbare Bedienelemente                                                       |
| Methoden          | A/B Testing                                        | Zwei Varianten an verschiedenen Gruppen testen                                                                |
| Methoden          | Proof of Concept                                   | Kleiner Test, ob eine Idee überhaupt machbar ist                                                              |
| Methoden          | MVP                                                | Einfachste Produktversion, die frühe Kunden zufriedenstellt und Feedback liefert                              |
| Methoden          | Lean Startup                                       | Schnell experimentieren und aus Kundenfeedback lernen                                                         |
| Methoden          | Innovation Lab                                     | Eigener Raum oder eigenes Team für neue Ideen und Geschäftsmodelle                                            |
| Methoden          | Growth Hacking                                     | Datengetriebene Experimente für schnelles, günstiges Wachstum                                                 |
| Neue Technologien | Digital Twin                                       | Virtuelle Kopie eines physischen Objekts zur Simulation                                                       |
| Neue Technologien | Quantum Computing                                  | Rechentechnik, die komplexe Probleme viel schneller lösen könnte                                              |
| Neue Technologien | AR / VR / MR                                       | Digitales über der realen Welt / völlig künstliche Umgebung / beides interagiert                              |
| Neue Technologien | Metaverse                                          | Gemeinsame virtuelle 3D-Welt                                                                                  |
| Neue Technologien | NFT                                                | Digitales Echtheitszertifikat für ein bestimmtes digitales Objekt                                             |
| Neue Technologien | Cryptocurrency                                     | Digitales Geld, durch Verschlüsselung gesichert                                                               |
| Neue Technologien | Robotics, 3D Printing, Drones, Autonomous Vehicles | Roboter, schichtweiser Druck aus digitalen Modellen, unbemannte Fluggeräte, selbstfahrende Fahrzeuge          |
| Neue Technologien | Smart City / Industry 4.0                          | Stadt nutzt Daten für Infrastruktur und Lebensqualität / Automatisierung und Datenaustausch in der Produktion |
| Wirtschaft        | Digital Transformation                             | Geschäftsweise und Wertschöpfung mit digitaler Technik grundlegend ändern                                     |
| Wirtschaft        | E-Commerce / Digital Marketing                     | Online kaufen und verkaufen / Werbung über digitale Kanäle                                                    |
| Wirtschaft        | SEO / SEM                                          | Bessere organische Platzierung in Suchmaschinen / bezahlte Suchanzeigen                                       |
| Wirtschaft        | Fintech                                            | Unternehmen, die Finanzdienstleistungen mit Technik erneuern                                                  |
| Wirtschaft        | Platform / Sharing / Gig Economy                   | Plattform vermittelt zwischen Nutzergruppen / Zugang statt Besitz / kurzfristige Aufträge statt Anstellung    |
| Wirtschaft        | Subscription / Freemium Model                      | Wiederkehrende Gebühr / Basis gratis, Premium kostenpflichtig                                                 |
| Wirtschaft        | Digital Native                                     | Mit digitaler Technik aufgewachsen                                                                            |

# Kapitel 2 – What Exactly Is a Business Information System (BIS)?

Ein BIS ist ein verbundenes Ganzes aus People, Processes, Hardware, Software und Data, das relevante Information dann verfügbar macht, wenn sie gebraucht wird. Das Kapitel behandelt jede der fünf Komponenten in einem eigenen Abschnitt.

## 2.1 Business Information System

- Enge Sicht: nur Elemente, die Geschäftsaufgaben direkt unterstützen.

- Weite Sicht: auch indirekt Beitragendes (analoger Kühlschrank im Restaurant, Navi im Dienstwagen, Berufserfahrung).

- Off-the-Shelf vs. Custom-Built: Standardkomponenten oder Individualentwicklung; das BIS muss zu Strategie, Größe und Branche passen.

## 2.2 Komponente 1: Processes

Prozess = Folge von Schritten, um eine Geschäftsaufgabe zu erledigen. Prozesse sind das Rückgrat: Ihre Struktur bestimmt, wie die anderen Komponenten zusammenwirken.

| Prozessart      | Definition                                   | Beispiel                                |
|-----------------|----------------------------------------------|-----------------------------------------|
| Operational     | Erzeugt das Produkt oder die Leistung        | Bestellung prüfen, packen, versenden    |
| Support         | Hält die Arbeit ohne Unterbrechung am Laufen | Defekten Lagerscanner reparieren        |
| Management      | Hilft Managern bei Entscheidungen            | Lieferverzug analysieren und reagieren  |
| Innovation      | Macht aus einer Idee eine Verbesserung       | Prototyp einer leiseren Lampe testen    |
| Compliance      | Sichert die Einhaltung von Regeln            | Sicherheitsaudit vor Freigabe           |
| Customer Facing | Gestaltet die Reaktion auf Kunden            | Lieferadresse ändern und bestätigen     |
| Sales           | Von der Anfrage zum Auftrag                  | Angebot erstellen, Auftrag anlegen      |
| Supply Chain    | Hält benötigtes Material verfügbar           | Stoff nachbestellen, Lieferung annehmen |

## 2.3 Komponente 2: People

Personen und Gruppen, die das BIS nutzen oder sich auf seine Informationen stützen, intern wie extern.

- Managers: sehen die Leistung der Organisation und entscheiden.

- Employees: erledigen ihre tägliche Arbeit damit.

- IT: hält das System verfügbar und sicher, steuert Zugriffe.

- Customers: verfolgen etwa den Bestellstatus.

- Suppliers: erkennen, was die Organisation braucht.

- Creditors: entscheiden über Kredite und überwachen Zahlungen.

- Owners: sehen, ob Ziele erreicht werden.

- Other Business Partners: koordinieren gemeinsame Arbeit (Logistikpartner, Handelsvertreter).

**IT-Rollen:** CTO (Technologiestrategie und -investitionen), IT Director (Tagesbetrieb und Budget der IT), Systems Administrator (Server, Benutzerkonten, Kerndienste), Database Administrator (Datenbanken sicher, schnell, wiederherstellbar), Network Engineer (Netze), Software Developer (Code), Cybersecurity Specialist (Schutz vor Angriffen), Help Desk Technician (Alltagsprobleme), Business Analyst (Geschäftsbedarf in technische Lösungen übersetzen), Data Analyst (Muster in Daten), Project Manager (IT-Projekte in Zeit und Budget), QA Tester (Software vor Release prüfen).

## 2.4 Komponente 3: Hardware

Hardware ist die physische Ausstattung, die das System arbeiten lässt. Die 13 Kategorien stehen mit Beispielen in der Tabelle unter Grundlagen 2.

## 2.5 Komponente 4: Software

- Software: Programme und Anweisungen, die der Hardware sagen, was und wie sie es tun soll.

- Systemsoftware vs. Anwendungssoftware; sieben Kategorien (Betriebssystem, Produktivität, Business Applications, Kommunikation & Kollaboration, Datenbankmanagement, Sicherheit & Utilities, Entwicklung).

- Business Application Software:

- ERP: verbindet die Arbeit aller Abteilungen in einem gemeinsamen System; Eingaben einer Abteilung stützen sofort die anderen.

- CRM: Beziehungen zu aktuellen und potenziellen Kunden; jede Interaktion stützt die nächste.

- SCM: plant Roh- und Warenfluss vom Lieferanten zum Kunden; verbindet erwartete Nachfrage mit Material und Produktion, zeigt Bestände und Lieferungen.

- Functional Area Software: Spezialprogramme für eine Abteilung (HR-Recruiting, Buchhaltung, Produktionsplanung).

- Project Management Software: alle Projektinformationen an einem Ort; planen, koordinieren, Fortschritt überwachen.

- Business Intelligence Tools: Daten aus ERP, CRM, SCM u. a. zusammenführen und als Reports und Dashboards aufbereiten.

## 2.6 Komponente 5: Data

Daten sind die Fakten und Aufzeichnungen, mit denen das System arbeitet.

- Drei Metakategorien: Master Data (wiederholt genutzte Stammdaten), Transactional Data (Aufzeichnung eines Geschäftsvorfalls, z. B. Rechnung), Analytical Data (für Reporting und Entscheidungen).

- 15 Kategorien: Customer, Financial, Product, Inventory, Employee, Operational, Market, Competitor, Supplier & Partner, Compliance & Legal, Communication, Research & Development, Geospatial & Location, Digital Behavior, Sensor & IoT Data.

## 2.7 The Big Picture

Die fünf Komponenten wirken nie isoliert: Jede Änderung an einer beeinflusst die anderen vier. Ein BIS lässt sich deshalb nicht optimieren, indem man nur einen Bereich (etwa die Software) verbessert.

# Kapitel 3 – Data Management and Business Analytics

Sieben Abschnitte führen vom einzelnen Datenwert über Datenmanagement und Datenbanken zu Analytics, BI und Analyseplattformen.

## 3.1 Data Types

Boolean (nur wahr/falsch), Integer (ganze Zahl), Float (Kommazahl), Date/Time, String (Text mit Buchstaben, Ziffern, Sonderzeichen), Image, Audio & Video, Object Data (mehrere zusammengehörige Werte in einem Objekt, etwa Name, Adresse, Kundennummer).

## 3.2 Internal and External Data

Interne Daten entstehen im Unternehmen, externe außerhalb.

## 3.3 Data Management

Daten über ihren gesamten Lebenszyklus sammeln, organisieren, pflegen und steuern. Sechs Komponenten:

1.  Data Storage: wo und wie Daten liegen, damit man sie wiederfindet.

2.  Data Quality: laufend prüfen, korrigieren, vervollständigen, aktualisieren.

3.  Data Governance: wer verantwortlich ist, wer zugreifen darf, welche Regeln gelten.

4.  Data Integration: Daten verschiedener Systeme gemeinsam nutzbar machen.

5.  Data Security: Schutz vor unbefugtem Zugriff, Diebstahl, Verlust.

6.  Metadata Management: Daten über Daten pflegen (Herkunft, Bedeutung, letzte Aktualisierung).

## 3.4 Databases

- Datenbank: speichert Daten dauerhaft und zentral; mehrere Nutzer und Anwendungen gleichzeitig. Ein DBMS speichert, liest, ändert und löscht. Welche Art passt, hängt von Menge, Struktur und Zweck der Daten ab.

| Typ                    | Prinzip                                                                                                                       | Geeignet für                                  | Grenze                                          |
|------------------------|-------------------------------------------------------------------------------------------------------------------------------|-----------------------------------------------|-------------------------------------------------|
| Relational             | Tabellen nach Themen; Spalte = Merkmal, Zeile = Datensatz; Primary Key identifiziert jeden Satz eindeutig; Abfragesprache SQL | Kleine bis mittlere, klar strukturierte Daten | Feste Tabellenstruktur                          |
| Non-relational (NoSQL) | Flexible Datenmodelle ohne einheitliche Tabellenspalten; können auf mehrere Server verteilt sein                                                      | Big Data, IoT, Social Media                   | –                                               |
| In-Memory              | Arbeitsdaten im RAM                                                                                                           | Live-Dashboards, sofortige Updates            | Datenverlust bei Stromausfall, begrenzt, teuer  |
| Object-oriented        | Objekte mit Unterobjekten (Gebäude → Stockwerke → Räume)                                                                      | Zusammenhängende Ganzheiten                   | Auswertung über die ganze Datenbank schwieriger |

- On-Premises vs. Cloud-Datenbank. Vorteile der Cloud: keine eigenen Server, skalierbar, Anbieter übernimmt Wartung, oft bessere Sicherheitswerkzeuge, automatische Backups. Nachteile: Daten bei Dritten, ohne Internet kein Zugriff, laufende Kosten können eigene Server übersteigen, Anbieterwechsel teuer, Speicherort kann rechtlich eingeschränkt sein.

## 3.5 Business Analytics

Große Datenmengen auswerten, um zu verstehen, was im Unternehmen geschieht, und besser zu entscheiden.

1.  Descriptive: Was ist passiert?

2.  Diagnostic: Warum ist es passiert?

3.  Predictive: Was wird passieren? (interne und externe Daten)

4.  Prescriptive: Was sollen wir tun?

## 3.6 Business Intelligence

BI führt Daten aus verschiedenen Quellen zusammen, bereitet sie auf und zeigt sie in Charts und Dashboards. Sie stützt vor allem die deskriptive, teils die diagnostische Analytics. BI und Business Analytics sind nicht dasselbe, werden im Alltag aber oft synonym verwendet.

## 3.7 Data Platforms for Analysis

- Data Warehouse: Daten aus allen Unternehmensteilen an einem Ort, ausschließlich für Analyse; schnelle Abfragen für Reports und Trends.

- Data Mart: kleiner Ausschnitt eines Warehouse für eine Abteilung; übersichtlicher und schneller.

- Data Lake: große Mengen unterschiedlicher Rohdaten in Originalform (Web, Social Media, Apps, IoT), noch nicht bereinigt; für spätere Analyse, Machine Learning oder unbekannte Zwecke.

# Kapitel 4 – Automation

Fünf Abschnitte zu regelbasierter Automation ohne AI: Abgrenzung zu AI, Technologien, Szenarien, Aufbau und Auswahl geeigneter Prozesse.

## 4.1 Automation vs. Artificial Intelligence

- Automation: Eine Maschine folgt festen Regeln, jedes Mal gleich, ohne menschliches Zutun; sie entscheidet nicht selbst über neue Situationen.

- AI: nutzt gelernte Muster, um eine Antwort vorherzusagen oder den nächsten Schritt zu wählen. AI-gestützte Automation behandelt Kapitel 5.

## 4.2 Automation Technologies

- In Business-Software eingebaut: vorhandene Funktionen aktivieren und Regeln festlegen.

- Workflow Automation: Arbeit läuft einen festen Pfad; bei Entscheidungen geht sie an eine Person und läuft danach automatisch weiter.

- System Integration: Programme tauschen Daten automatisch aus, ohne erneute Eingabe.

- Robotic Process Automation (RPA): Software-Bot wiederholt Klicks und Eingaben in Bildschirmmasken; kein physischer Roboter.

- Template-based Document Processing: liest oder füllt feste Felder eines bekannten Layouts, ohne den Inhalt zu deuten.

- Industrial Control: Steuerungscomputer bedienen Maschinen nach Programm und Sensorsignal.

- Programmed Robots: führen vorab festgelegte physische Bewegungen aus; dafür ist keine AI nötig.

## 4.3 Business Automation Scenarios

| Technologie                        | Szenarien                                                                                                                                                             |
|------------------------------------|-----------------------------------------------------------------------------------------------------------------------------------------------------------------------|
| In Business-Software eingebaut     | Regelbasierte Erstattung, Garantieprüfung, Rechnung und Mahnung, Terminbuchung, Payroll, Bestellvorschlag bei Meldebestand, geplante IT-Wartung, Social-Media-Planung |
| Workflow Automation                | Sales Follow-up, Spesenfreigabe, Onboarding, Mitarbeitergespräche planen, regelbasiertes Ticket-Routing                                                               |
| System Integration                 | Order Fulfillment, Bankabgleich, monatliches Finanzreporting                                                                                                          |
| RPA                                | Dateneingabe in Altsystemen ohne direkte Schnittstelle                                                                                                                |
| Template-based Document Processing | Felder aus Standardrechnung in die Buchhaltung übernehmen                                                                                                             |
| Industrial Control                 | Produktionsablauf per SPS (PLC) steuern, bei Fehler Alarm                                                                                                             |
| Programmed Robots                  | Regelbasierte Lagerlogistik mit gespeicherten Plätzen und Routen                                                                                                      |

In der Praxis kombiniert ein Szenario oft mehrere Technologien.

## 4.4 Setting Up an Automation

- Trigger: Ereignis, das den Ablauf startet (Formular, Uhrzeit, Meldebestand).

- Rules: vordefinierte Anweisungen, denen das System folgt.

- Action: der nächste Schritt, den das System ausführt.

- Exception: Ein Mensch übernimmt, wenn die Regeln den Fall nicht abdecken.

Zusätzlich legt der Manager fest, welche Daten die Automation braucht.

## 4.5 Choosing the Right Automation Candidates

Nur automatisieren, wenn alle vier Fragen mit Ja beantwortet sind:

- Reward: Stützt es direkt ein strategisches Ziel?

- Rhythm: Kommt der Prozess oft genug vor?

- Rules: Gibt es klare Anweisungen und Eingabedaten in einheitlichem Format?

- Risk: Läuft es zuverlässig ohne häufige Sonderfälle oder menschliche Schlüsselentscheidungen?

# Kapitel 5 – Artificial Intelligence (AI)

Zehn Abschnitte: was AI ist, wie sie entwickelt wird, wie neuronale Netze rechnen, welche Typen und Modelle es gibt, welche Fähigkeiten Manager brauchen und welche Risiken bestehen.

## 5.1 What Is Artificial Intelligence?

AI ist Software, die Aufgaben erfüllt, die sonst menschliche Intelligenz brauchen: vorhersagen, Entscheidungen stützen oder treffen, empfehlen, Inhalte erzeugen. Sie braucht keine Regel für jeden Fall, sondern lernt Muster aus Beispielen. Dieses Lernen heißt Machine Learning.

## 5.2 The Nine Steps of Developing AI

1.  Lernziel definieren.

2.  Erfolg messbar machen.

3.  Trainingshardware bereitstellen.

4.  Trainingsdaten sammeln und aufbereiten.

5.  Trainingscode schreiben.

6.  Training starten, Muster erkennen.

7.  Mit ungesehenen Beispielen testen und gegen Schritt 2 messen.

8.  Einstellungen anpassen und erneut testen, bis die Kriterien erfüllt sind.

9.  Abschlusstest mit Beispielen, die weder im Training noch beim Anpassen vorkamen.

## 5.3 Neural Networks

- Neuronales Netz: Rechenmodell, das aus Beispielen Muster lernt, um neue Eingaben zu verarbeiten.

- Neuron: kleine Recheneinheit, vereinfacht eine mathematische Formel.

- Input Layer (nimmt Zahlenwerte auf) → Hidden Layers (verarbeiten und geben weiter) → Output Layer (berechnet das Ergebnis).

- Weights: bestimmen, wie stark ein Eingabewert zählt. Bias: verschiebt die Summe. Activation Function: wandelt sie in das weitergegebene Signal um.

- Training: Forward Pass (Vorhersage) → Loss (Fehler gegenüber richtiger Antwort) → Backpropagation (rückwärts berechnen, wie Gewichte den Fehler beeinflussen, und anpassen) → wiederholen.

## 5.4 AI Black Boxes

Modell, dessen Weg zum Ergebnis für Menschen praktisch nicht nachvollziehbar ist, weil zu viele Berechnungen ineinandergreifen.

## 5.5 The Six Functional Types of AI

- Predictive AI: sagt Zukünftiges voraus (Nachfrage, Maschinenausfall).

- Classification & Recognition AI: erkennt, was etwas ist, und ordnet es einer Kategorie zu (defekte Teile auf Fotos, Spracherkennung).

- Recommendation AI: schlägt passende Optionen vor (Produkte, Filme).

- Decision Support & Optimization AI: wählt die beste Handlung oder hilft dabei (Routen, Schichtpläne).

- Generative AI: erzeugt neue Inhalte (Text, Bild, Audio, Video, Code).

- Agentic AI: plant und führt Schritte zu einem vorgegebenen Ziel selbst aus.

## 5.6 AI Model

Das Modell ist der Motor hinter einem AI-Tool; es erklärt, warum ein Tool Gästezahlen vorhersagt und ein anderes Musikvideos erzeugt. Fast alle Modelle durchlaufen die neun Schritte, unterscheiden sich aber in Aufbau und Training.

## 5.7 Eleven Common Types of AI Models

| Modell                  | Leistung                                                 |
|-------------------------|----------------------------------------------------------|
| Large Language Model    | Text verarbeiten, auf Fragen und Anweisungen antworten   |
| Computer Vision         | Bilder und Videos analysieren und erkennen               |
| Speech Recognition      | Gesprochene Sprache → Text                               |
| Text-to-Speech          | Text → gesprochene Sprache                               |
| Multimodal              | Mehrere Informationsarten verarbeiten oder erzeugen      |
| Diffusion               | Neue Inhalte erzeugen, z. B. Bild aus Beschreibung       |
| Time-Series Forecasting | Künftige Werte aus vergangener Zeitreihe                 |
| Recommendation          | Optionen aus Mustern früherer Entscheidungen vorschlagen |
| Classification          | Eingabe einer Kategorie zuordnen                         |
| Regression              | Einen Zahlenwert schätzen                                |
| Anomaly Detection       | Ungewöhnliche Eingaben oder Verhalten erkennen           |

## 5.8 Narrow AI, AGI, ASI

- Narrow AI (Weak AI): für eine oder wenige Aufgaben trainiert (Chatbot, Übersetzung, Gesichtserkennung).

- AGI (im Alltag Strong AI): mögliche künftige AI, die viele Aufgaben etwa auf Menschenniveau löst.

- ASI: hypothetische AI, die den Menschen in fast allen Denkbereichen übertrifft.

## 5.9 Nine Must-Have Skills for Using AI as a Manager

Geeignete Aufgaben erkennen, passendes Tool wählen, klare Prompts schreiben, komplexe Aufgaben zerlegen, Ergebnisse iterativ verbessern, Datenschutz und Vertraulichkeit wahren, Workflows zwischen Mensch und AI gestalten, den AI-Beitrag dokumentieren, Fachwissen zur Prüfung einsetzen.

## 5.10 The Risks and Limitations of AI

| Risiko                         | Bedeutung                                                                                                             |
|--------------------------------|-----------------------------------------------------------------------------------------------------------------------|
| Hallucinations                 | Plausibel klingende, aber falsche oder erfundene Inhalte; AI berechnet wahrscheinliche Wortfolgen, statt zu verstehen |
| Limited Common Sense           | Übersieht Alltagskontext                                                                                              |
| Limited Knowledge              | Veraltetes Wissen aus den Trainingsdaten                                                                              |
| Susceptibility to Errors       | Gut in bekannten, fehleranfällig in neuen Situationen                                                                 |
| Limits of Reasoning            | Logisch klingende Antworten ohne verlässliche Regelanwendung                                                          |
| Bias                           | Systematische Benachteiligung von Personen oder Gruppen                                                               |
| Overreliance                   | Ungeprüfte Übernahme von Vorschlägen                                                                                  |
| Skill Erosion                  | Fähigkeiten verkümmern durch ständiges Delegieren                                                                     |
| Accountability Gaps            | Unklar, wer bei Fehlern verantwortlich ist                                                                            |
| Intellectual Property Risks    | Unklar, ob Rechte verletzt werden oder wem sie gehören                                                                |
| Data Privacy Violations        | Unzulässige Verarbeitung oder Eingabe personenbezogener Daten in AI-Tools kann gegen Datenschutzrecht verstoßen                                                        |
| Misinformation & Deepfakes     | Täuschend echte, falsche Inhalte                                                                                      |
| Job Displacement               | Jobs fallen weg, neue verlangen andere Fähigkeiten                                                                    |
| Concentration of Power         | Abhängigkeit von wenigen Anbietern                                                                                    |
| Surveillance & Loss of Privacy | AI erschließt Privates, das nie offengelegt wurde                                                                     |
| Autonomous Weapons             | Angriff auf falsche Ziele, bevor ein Mensch eingreifen kann                                                           |

# Kapitel 6 – Cybercrime and Cybersecurity

Sieben Abschnitte: Grundlagen, technische Angriffe, Social Engineering, Web Tracking, Schutzmaßnahmen, Risk Chain und Risk Tolerance.

## 6.1 Cybercrime – Basics

- Cybercrime: jede illegale Aktivität über oder gegen digitale Systeme; zwei Kategorien, oft kombiniert.

- Kosten: direkter finanzieller Schaden, Betriebsstillstand, Wiederherstellung, Strafen bei verletzten Pflichten, Schadenersatz und Rechtskosten, Verlust oder Zerstörung von Information, Reputationsschaden.

## 6.2 Category 1: Technical Attacks

Greifen Computersysteme mit Schadcode an und nutzen Schwachstellen.

| Angriff              | Definition                                                                         |
|----------------------|------------------------------------------------------------------------------------|
| Brute Force          | Automatisiert viele Passwort- oder Schlüsselkombinationen probieren                |
| Drive-by Download    | Malware lädt sich beim Besuch einer manipulierten Website automatisch              |
| Session Hijacking    | Aktive Sitzung durch gestohlene Sitzungsdaten übernehmen                           |
| DNS Spoofing         | Manipulierte Namensauflösung leitet auf gefälschte Seiten                          |
| Exploit Kit          | Findet Schwachstellen automatisch und setzt passende Exploits ein                  |
| Keylogger            | Zeichnet Tastatureingaben auf                                                      |
| Botnet               | Netz gekaperter Geräte, ferngesteuert für koordinierte Angriffe                    |
| Man-in-the-Middle    | Fängt Kommunikation zwischen zwei Parteien heimlich ab und verändert sie eventuell |
| Cross-Site Scripting | Schadskript in vertrauenswürdiger Website, läuft im Browser des Nutzers            |
| Zero-Day Exploit     | Nutzt eine unbekannte Lücke, bevor ein Patch existiert                             |
| SQL Injection        | Manipuliert unsichere Datenbankabfragen, um Daten zu verändern oder auszulesen     |
| DDoS                 | Überflutet System oder Netz mit Datenverkehr, Dienst fällt aus                     |
| Ransomware           | Verschlüsselt Daten und fordert Lösegeld für den Schlüssel                         |
| Malware              | Oberbegriff für Schadsoftware                                                      |

## 6.3 Category 2: Social Engineering Attacks

Nutzen menschliche Psychologie, um an Informationen oder Zugang zu kommen.

| Angriff           | Definition                                                             |
|-------------------|------------------------------------------------------------------------|
| Tech Support Scam | Angreifer gibt sich als technischer Support aus                        |
| Dumpster Diving   | Sensible Information aus unsachgemäß entsorgtem Material               |
| Impersonation     | Auftreten als vertrauenswürdige Person                                 |
| Tailgating        | Unbefugter folgt einer befugten Person in einen geschützten Bereich    |
| Pretexting        | Erfundene, glaubwürdige Geschichte, um Vertrauliches zu erhalten       |
| Whaling           | Phishing gezielt gegen Führungskräfte                                  |
| Baiting           | Köder (Angebot, Gegenstand) löst schädliche Aktion aus                 |
| Watering Hole     | Infiziert Websites, die eine bestimmte Zielgruppe nutzt                |
| Scareware         | Gefälschte Sicherheitswarnungen erschrecken Nutzer                     |
| Quid pro quo      | Hilfe oder Vorteil gegen sensible Information                          |
| Spear Phishing    | Auf eine Person oder Organisation zugeschnittenes Phishing             |
| Vishing           | Phishing per Anruf oder Voicemail                                      |
| Smishing          | Phishing per SMS                                                       |
| Phishing          | Betrügerische Nachrichten, die zur Preisgabe sensibler Daten verleiten |

## 6.4 Web Tracking

- Web Tracking: Erfassen des Online-Verhaltens (Seiten, Verweildauer, Klicks, Suchen, Käufe, Standort, Gerät), um Profile zu bilden.

- Cookies: kleine Textdateien, die Nutzer wiedererkennen (Login, Warenkorb). Session Cookies verschwinden beim Schließen des Browsers, Persistent Cookies bleiben eine Frist lang, Third-Party Cookies folgen Nutzern über mehrere Websites.

- Local Storage: speichert größere Datenmengen auf dem Gerät.

- Heat Maps: zeigen, wo geklickt, gescrollt und verweilt wird.

- Tracking Pixels (Web Beacons): unsichtbare Bilder in Mails oder Seiten, melden Öffnen, Zeit, IP-Adresse, Browser.

- Digital Fingerprinting: erkennt Nutzer anhand von Geräte- und Browsermerkmalen, auch ohne Cookies.

- In der EU nur DSGVO-konform zulässig.

## 6.5 Cybersecurity

Technische Werkzeuge und sichere Arbeitsweisen gegen unbefugten Zugriff, Missbrauch und unerwünschte Änderung:

- Backups und Recovery (Wiederherstellung testen), Incident Response Planning, Security Monitoring.

- Encryption (nur mit Schlüssel lesbar), Firewalls (Verkehr nach Regeln erlauben oder blocken), Email Filtering.

- Secure Configuration (sichere Einstellungen, Standardpasswörter ersetzen), Updates und Patching, Antivirus/Endpoint Protection.

- Security Policies, Security Awareness Training, Access Control (wer darf was), Password Managers, Multifactor Authentication (mindestens zwei Faktoren).

## 6.6 The Risk Chain

Schrittmodell, wie aus einem Risiko ein Schaden wird, und wo man eingreifen kann:

1.  Threat: Hacker, Insider-Missbrauch.

2.  Vulnerability: ungepatchte Systeme, schwache Passwörter, schlechte Zugriffskontrolle.

3.  Attack Path: Malware-Mail, offener Netzwerkport.

4.  Trigger: Klick auf Phishing-Link, weitergegebenes Passwort.

5.  Risk Event: Datendiebstahl, Systemausfall.

6.  Impact: finanzieller Verlust, Reputationsschaden, Stillstand.

## 6.7 Risk Tolerance

- Risk Tolerance: wie viel Cyberrisiko ein Unternehmen zu akzeptieren bereit ist.

- Risk Corridor: akzeptierter Bereich.

- Risk Ceiling: höchstes akzeptables Risiko; darüber muss gegengesteuert werden.

- Risk Floor: darunter wird geprüft, ob weitere Senkung ihre Kosten und den Verwaltungsaufwand noch rechtfertigt.

# Kapitel 7 – Digital Compliance and Corporate Digital Responsibility (CDR)

Fünf Rechtsbereiche und CDR. Compliance fragt, was gesetzlich gilt; CDR fragt zusätzlich, ob der Einsatz fair und verantwortlich ist.

## 7.1 DSGVO und österreichisches DSG

- Was geschützt ist: Menschen bei der Verarbeitung personenbezogener Daten. Personenbezogen = auf eine bestimmte oder bestimmbare Person beziehbar, auch eine Kundennummer. Schon Erheben, Speichern, Weitergeben ist Verarbeitung. Das DSG verankert das Grundrecht auf Datenschutz.

- Rechtsgrundlagen: Vertragserfüllung (Lieferadresse), rechtliche Verpflichtung (Rechnungen aufbewahren), berechtigtes Interesse (darf die Rechte der Person nicht überwiegen), Einwilligung (aktiv, frei, informiert, zweckbezogen, jederzeit widerrufbar).

- Grundsätze: Zweckbindung, Datenminimierung, Richtigkeit, Speicherbegrenzung (außer Aufbewahrungspflicht), Transparenz.

- Betroffenenrechte: Auskunft, Berichtigung, Löschung, Einschränkung, Widerspruch, Datenübertragbarkeit; Antwort in der Regel binnen eines Monats.

- Verantwortung: Controller bestimmt Zweck und Mittel; Processor verarbeitet weisungsgebunden mit Auftragsverarbeitungsvertrag (Fitnessstudio und Druckerei).

- Schutz: angemessene technische und organisatorische Maßnahmen; Einhaltung muss nachweisbar sein.

- Datenpanne: Controller prüft und dokumentiert; bei Risiko Meldung an die Datenschutzbehörde ohne unnötigen Verzug, möglichst binnen 72 Stunden; bei hohem Risiko auch die Betroffenen. Strafen bis 10 Mio. € / 2 % bzw. 20 Mio. € / 4 % des weltweiten Vorjahresumsatzes, jeweils der höhere Betrag.

## 7.2 ePrivacy-Richtlinie und TKG 2021

- Schutzgegenstand: Vertraulichkeit elektronischer Kommunikation, Zugriff auf Endgeräte, Direktwerbung per E-Mail und SMS.

- Cookies und ähnliche Technik (Local Storage, Fingerprinting): Für nicht notwendige Zugriffe vorherige, freiwillige, informierte, aktive Einwilligung; vorangekreuzte Kästchen oder Weitersurfen reichen nicht; Ablehnen so einfach wie Zustimmen.

- Ausnahme: reine Nachrichtenübermittlung oder für einen ausdrücklich gewünschten Dienst unbedingt nötig (Warenkorb) – Werbetracking fällt nicht darunter.

- E-Mail- und SMS-Werbung: grundsätzlich Einwilligung; Bestandskundenausnahme nur, wenn Adresse aus Kauf, eigene ähnliche Produkte, einfache Abmeldung bei Erhebung und in jeder Nachricht, kein Widerspruch und kein Eintrag in der ECG-Liste.

- Verhältnis zur DSGVO: TKG regelt den Zugriff aufs Gerät; werden dabei personenbezogene Daten verarbeitet, gilt zusätzlich die DSGVO.

## 7.3 EU AI Act

- Regelt Entwicklung und Nutzung von AI, gilt direkt in Österreich; entscheidend ist der konkrete Verwendungszweck.

- Provider: entwickelt ein AI-System und bringt es unter eigenem Namen in Verkehr. Deployer: nutzt es beruflich in eigener Verantwortung.

- Risikostufen: unannehmbar, hoch, Transparenzrisiko, minimal; je höher das Risiko, desto strenger die Pflichten.

- Verboten: u. a. Social Scoring mit ungerechtfertigten Nachteilen, Ausnutzen von Schwächen (Alter, Behinderung, Notlage).

- Hochrisiko (z. B. Bewerberauswahl, Kreditwürdigkeit): nicht verboten, aber Risikomanagement, Dokumentation, menschliche Aufsicht mit Kompetenz und Eingriffsbefugnis, Protokolle.

- Transparenz: Chatbots und Deepfakes erkennbar machen. AI Literacy: Provider und Deployer müssen die Kompetenz ihrer Leute fördern.

- Strafen: verbotene Praktiken 35 Mio. € / 7 %; andere Pflichten inkl. Transparenz 15 Mio. € / 3 %; falsche Angaben 7,5 Mio. € / 1 %; KMU jeweils der niedrigere Betrag.

- Fristen: Verbote und AI Literacy seit 2. 2. 2025; Transparenz seit 2. 8. 2026; Hochrisiko ab 2. 12. 2027; Hochrisiko in regulierten Produkten ab 2. 8. 2028.

## 7.4 Rechtliche Grundlagen für Webshops in Österreich

- GewO: Gewerbeberechtigung für gewerblichen Warenverkauf, auch online.

- ECG: Name, Adresse, E-Mail und weiterer schneller Kontaktweg; bei Preisen klar, ob Steuern und Versand enthalten sind; Bestellablauf vorab erklären, Eingabefehler korrigierbar.

- UGB: bei Firmenbucheintrag Firma, Rechtsform, Sitz, Firmenbuchnummer, Firmenbuchgericht.

- MedienG: Offenlegung des Medieninhabers; Umfang hängt vom Inhalt der Website ab, nicht von der Unternehmensgröße.

## 7.5 NIS2-Richtlinie und NISG 2026

- Zweck: Cybersicherheit wichtiger Dienste; NISG 2026 seit 1. 10. 2026 in Kraft.

- Erfasst: bestimmte Sektoren (Energie, Gesundheit, digitale Dienste, Teile der Industrie), in der Regel ab mittlerer Größe (≥ 50 Beschäftigte oder \> 10 Mio. € Umsatz und Bilanzsumme). IT-Nutzung allein genügt nicht.

- Essential Entities (groß, hochkritische Sektoren, strengere Aufsicht) vs. Important Entities.

- Pflichten: Registrierung beim Bundesamt für Cybersicherheit, Risikomanagement inkl. Lieferkette, Prüfungen, Wiederanlauf nach Angriffen.

- Meldung an das CSIRT: Frühwarnung ≤ 24 h, Vorfallsmeldung ≤ 72 h, Abschlussbericht ≤ 1 Monat nach Vorfallsmeldung (sonst Fortschrittsbericht).

- Strafen: Essential 10 Mio. € / 2 %, Important 7 Mio. € / 1,4 %, jeweils der höhere Betrag; bei Personendaten zusätzlich DSGVO-Meldepflicht.

## 7.6 Corporate Digital Responsibility

- CDR: Verantwortung dafür, wie die Nutzung digitaler Technik Menschen und Umwelt beeinflusst; ergänzt gesetzliche Pflichten, ersetzt sie nicht.

- Umgang mit Systemen und Daten: ethisch nutzen, Risiken früh bedenken (Privacy by Design), Zweckbindung und Datenminimierung, Dienste und Daten schützen (Need-to-know).

- Umgang mit Menschen: unfaire Benachteiligung prüfen und beheben, Transparenz (erkennbar, wenn AI antwortet), informierte Entscheidungen ohne Dark Patterns (Design, das zu ungewollten Entscheidungen lenkt), digitale Inklusion.

- Weitere Wirkungen: Mitarbeitende auf neue Aufgaben vorbereiten, ökologische Folgen (Energie, Gerätetausch), Wirkung auf die Gesellschaft.

- Verantwortung: klar zuweisen, wer Systeme überwacht und eingreift; auch bei Fremdsoftware bleibt das Unternehmen verantwortlich.

# Kapitel 8 – Digitalization Projects

Vier Abschnitte: was ein Digitalisierungsprojekt ist, warum Projekte scheitern, die zehn Phasen und Change Management mit der Change Curve.

## 8.1 Digitalization Projects

- Ein Digitalisierungsprojekt löst konkrete Probleme und stützt strategische Ziele: erst die wichtigsten Probleme bestimmen, dann die Technik wählen.

- Projektportfolio: Mehrere gleichzeitige Projekte werden gemeinsam gesteuert, Abhängigkeiten berücksichtigt; dafür ist ein eigenes Team zuständig.

## 8.2 Common Reasons Why Digitalization Projects Fail

1.  Keine gemeinsame strategische Richtung: einzelne Technologiekäufe statt koordinierter Veränderung.

2.  Unklare Prioritäten: unklar, welche Probleme am wichtigsten sind.

3.  Prozesse nicht verbessert: alte Schwächen werden ins neue System übernommen.

4.  Abhängigkeiten ignoriert.

5.  Keine zentrale Verantwortung für die Gesamttransformation.

6.  Überlastete Mitarbeitende: Transformation kommt zur normalen Arbeit dazu.

7.  Projekte konkurrieren um dieselben Ressourcen und Entscheider.

8.  Zu wenig Investition in Change Management.

## 8.3 Phases of a Digitalization Project

1.  Needs Identification & Strategic Alignment: Probleme, Nutzerbedarf, Ziele und Anforderungen klären.

2.  Feasibility & Business Case: Machbarkeit mit Zeit, Geld, Know-how; Nutzen gegen Kosten. Quick Wins = hoher Nutzen bei wenig Aufwand.

3.  Process Design: künftige Abläufe und Zuständigkeiten festlegen, Schwächen beheben, daraus technische Anforderungen ableiten.

4.  System Design: Architektur des BIS planen, mit Wissen der Fachabteilungen.

5.  Development & Configuration: Hardware beschaffen, Software entwickeln und einstellen; in Sprints mit frühem Feedback.

6.  Integration & Data Migration: neue Teile anbinden, bereinigte Daten übernehmen; der Betrieb läuft im Altsystem weiter.

7.  Testing & Validation: Einzelteile und Zusammenspiel testen, mit künftigen Nutzern prüfen.

8.  Pilot & Deployment Preparation: ausgewählte Nutzer arbeiten im echten Tagesgeschäft eines begrenzten Bereichs; Schulungen vorbereiten.

9.  Rollout, Adoption & Change Management: in koordinierten Wellen; Parallelbetrieb mit fixem Abschaltdatum.

10. Benefits Realization & Continuous Improvement: Nutzen messen statt schätzen, gemeinsam mit Nutzern verbessern.

## 8.4 Change Management

- Change Management: hilft Mitarbeitenden, mit Veränderungen umzugehen und neue Routinen tatsächlich zu übernehmen. Geplant ab Process Design, weiterentwickelt nach dem Pilot.

- Instrumente: rollenspezifische Schulung, Mentoring (persönliche Begleitung), Change Champions (Ansprechpersonen in den Abteilungen, die den Wandel aktiv unterstützen).

- Shadow IT: Technik, die ohne Wissen oder Freigabe der IT genutzt wird.

## 8.4.1 The Change Curve

Mögliche emotionale Reaktionen auf Veränderung; nicht jeder durchläuft alle Phasen oder in dieser Reihenfolge.

1.  Shock: Die Ankündigung verunsichert.

2.  Denial: „Unnötig, betrifft mich nicht“, weiter wie bisher.

3.  Frustration: Ärger über verlorene Routinen.

4.  Depression: emotionaler Tiefpunkt, Rückzug (keine medizinische Diagnose).

5.  Experimentation: Neues ausprobieren, lernen, was funktioniert.

6.  Decision: erste Erfolge stärken das Vertrauen in die eigenen Fähigkeiten.

7.  Integration: Das Neue ist Gewohnheit.

# Quellenverzeichnis

Öffentlich erreichbare Quellen sind mit Link angegeben (abgerufen am 17. November 2026). Die Kursunterlagen sind nicht öffentlich zugänglich; sie sind genannt, damit nachvollziehbar ist, worauf sich der Text stützt. Die Kürzel entsprechen den Herkunftsangaben im Text.

## Kursunterlagen (nicht öffentlich)

- **Study Guide:** STAGES – Digitalizing Organizations, Study Guide, Kapitel 1–8 (englischsprachige Kapitelzusammenfassungen). Lernplattform STAGES (Anmeldung erforderlich). Grundlage für Kapitel 1–8 und Teile von Grundlagen 2.

- **Pomberger:** Skriptum „Algorithmen und Datenstrukturen“, Johannes Kepler Universität Linz, Kapitel 7–9 (Rekursion, Komplexität, Sortieralgorithmen). Verwendet in Grundlagen 1 und 4.

## Öffentlich erreichbare Quellen

- **CS Unplugged:** Bell, T.; Witten, I. H.; Fellows, M.: Computer Science Unplugged. Deutsche Fassung des Projekts ADA, TU Wien, Dezember 2020. Projektseite: <https://www.csunplugged.org/de/>. Verwendet in Grundlagen 1–5.

- **CS50:** Harvard University: CS50x 2023, Lecture 3 „Algorithms“ (Notizen, Folien, Video): <https://cs50.harvard.edu/x/2023/notes/3/>. Verwendet in Grundlagen 4.

- **lernhelfer.de:** Rechenhilfsmittel, Chronologie: <https://www.lernhelfer.de/schuelerlexikon/mathematik/artikel/rechenhilfsmittel-chronologie>. Verwendet in Grundlagen 1.

- **Sortier-Visualisierungen:** Toptal, Sorting Algorithms Animations: <https://www.toptal.com/developers/sorting-algorithms>; Galles, D. (University of San Francisco), Comparison Sorting Visualization: <https://www.cs.usfca.edu/~galles/visualization/ComparisonSort.html>.

- **Fragenkatalog:** simon-lost-in-cache: computer-science-training-test, Datei questions.json (120 Übungsfragen zu Kapitel 1–8 des Study Guide), GitHub: <https://github.com/simon-lost-in-cache/computer-science-training-test>. Zum Abgleich verwendet.

## Rechtsquellen zu Kapitel 7

Kapitel 7 gibt den Study Guide wieder. Die Rechtstexte sind zur Überprüfung verlinkt; österreichische Gesetze in der geltenden Fassung im Rechtsinformationssystem des Bundes (RIS).

- **DSGVO:** Verordnung (EU) 2016/679: <https://eur-lex.europa.eu/eli/reg/2016/679/oj>

- **DSG:** Datenschutzgesetz, BGBl. I Nr. 165/1999: <https://www.ris.bka.gv.at/GeltendeFassung.wxe?Abfrage=Bundesnormen&Gesetzesnummer=10001597>

- **ePrivacy-Richtlinie:** Richtlinie 2002/58/EG: <https://eur-lex.europa.eu/eli/dir/2002/58/oj>

- **TKG 2021:** Telekommunikationsgesetz 2021, BGBl. I Nr. 190/2021: <https://www.ris.bka.gv.at/GeltendeFassung.wxe?Abfrage=Bundesnormen&Gesetzesnummer=20011678>

- **AI Act:** Verordnung (EU) 2024/1689: <https://eur-lex.europa.eu/eli/reg/2024/1689/oj>

- **GewO 1994:** Gewerbeordnung 1994, BGBl. Nr. 194/1994: <https://www.ris.bka.gv.at/GeltendeFassung.wxe?Abfrage=Bundesnormen&Gesetzesnummer=10007517>

- **ECG:** E-Commerce-Gesetz, BGBl. I Nr. 152/2001: <https://www.ris.bka.gv.at/GeltendeFassung.wxe?Abfrage=Bundesnormen&Gesetzesnummer=20001703>

- **UGB:** Unternehmensgesetzbuch: <https://www.ris.bka.gv.at/GeltendeFassung.wxe?Abfrage=Bundesnormen&Gesetzesnummer=10001702>

- **MedienG:** Mediengesetz, BGBl. Nr. 314/1981: <https://www.ris.bka.gv.at/GeltendeFassung.wxe?Abfrage=Bundesnormen&Gesetzesnummer=10000719>

- **NIS2-Richtlinie:** Richtlinie (EU) 2022/2555: <https://eur-lex.europa.eu/eli/dir/2022/2555/oj>

- **NISG 2026:** Netz- und Informationssystemsicherheitsgesetz 2026, BGBl. I Nr. 94/2025, in Kraft seit 1. Oktober 2026: <https://www.ris.bka.gv.at/GeltendeFassung.wxe?Abfrage=Bundesnormen&Gesetzesnummer=20013065>


## Zusätzliche Quellen der Korrekturfassung

Die folgenden Quellen wurden **erst für die Überarbeitung der Markdown-Fassung** herangezogen. Sie gehören nicht zum ursprünglichen Quellenverzeichnis des Verfassers.

- **Science Museum Group:** [Charles Babbage](https://collection.sciencemuseumgroup.org.uk/people/cp36993) – kleines experimentelles Modell der Difference Engine (1822).
- **Smithsonian, National Museum of American History:** [Log Book With Computer Bug](https://www.americanhistory.si.edu/collections/object/nmah_334663) – Mottenfund 1947; älterer Gebrauch des Wortes „Bug“.
- **Computer History Museum:** [First Transistor (1947)](https://www.computerhistory.org/revolution/digital-logic/12/273).
- **Computer History Museum:** [Timeline of Computer History](https://www.computerhistory.org/timeline/computers/) – Personal-Computer-Geschichte, Apple I und Apple II.
- **OpenDSA / Virginia Tech:** [Empirical Comparison of Sorting Algorithms](https://opendsa.cs.vt.edu/ODSA/Books/CS3/html/SortingEmpirical.html) – Leistungsunterschiede zwischen Sortierverfahren.
- **Algorithmusübersicht:** [Planar Graph Coloring](https://algorithm.tamnd.com/planar-graph-coloring/) – Unterschied zwischen Vier- und Dreifärbung planarer Graphen.

## Weiterführende Medien (nicht als Quelle verwendet)

- Harvard CS50 – Full Computer Science University Course (YouTube): <https://www.youtube.com/watch?v=8mAITcNt710>

- Studyflix: Theoretische Informatik: <https://studyflix.de/informatik/thema/theoretische-informatik-46>

- KI – Die letzte Erfindung der Menschheit? (YouTube): <https://www.youtube.com/watch?v=lHlxx9gS7Ek>

- Wie funktioniert eigentlich Machine Learning? (YouTube): <https://www.youtube.com/watch?v=ya_6I9IVMzY>

- ChatGPT, Gemini, Claude & Co erklärt: Wie Maschinen Sprache verstehen – Terra X Lesch & Co (YouTube): <https://www.youtube.com/watch?v=MsqL9fzOzXU>

- Was ist Künstliche Intelligenz? – Die Maus, WDR (YouTube): <https://www.youtube.com/watch?v=_80pKGuyKWc>
