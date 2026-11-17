# Änderungsprotokoll – Lernguide Introduction to Computer Science

**Ausgangsdokument:** `Lernguide_Intro_to_CS.docx`, Claudiu Dangulea, 17. November 2026.  
**Zieldokument:** `Lernguide_Intro_to_CS_korrigiert.md`.  
**Seitenangaben:** Seiten der Word-Originalfassung bzw. ihrer 47-seitigen Ansicht, nicht Markdown-Seiten.

## Inhaltliche Änderungen

| Nr. | Originalseite | Vorher | Nachher / Begründung |
|---|---|---|---|
| 1 | 7 | „1822 – Babbages Difference Engine funktioniert“ | 1822 demonstrierte Babbage eine kleine Versuchsanordnung; die vollständige Maschine wurde damals nicht fertiggestellt. |
| 2 | 8 | „1940er – Ein Käfer im Relais ...“; „Herkunft von Bug und Debugging“ | 1947 wurde eine **Motte** im Harvard Mark II gefunden; „Bug“ war in der Technik bereits vorher gebräuchlich. |
| 3 | 8 | „1951 – Transistor technisch realisiert“ | **1947**: erster funktionsfähiger Transistor bei Bell Labs. |
| 4 | 8 | „1978 – Erste Personal Computer (Apple)“ | **1976 Apple I, 1977 Apple II**; andere frühe Personal Computer gab es ebenfalls. |
| 5 | 8 | „erst dadurch kann ein Programm verzweigen“ (Stored Program) | Korrigiert: Gemeinsamer adressierbarer Speicher von Programmanweisungen und Daten; Verzweigungen sind auch mit anderen Architekturen möglich. |
| 6 | 14 | „Quicksort – im Mittel am schnellsten“ | Präzisiert auf durchschnittlich **O(n log n)**, Worst Case **O(n²)**; nicht pauschal schnellster Algorithmus. |
| 7 | 14 | „Bucket Sort – O(n), weil er nicht vergleicht“ | Präzisiert auf **O(n + k)** unter geeigneten Annahmen mit `k` Buckets. |
| 8 | 14 | „n log n ist die Untergrenze für vergleichsbasiertes Sortieren“ | Auf **Ω(n log n) im Worst Case** präzisiert. |
| 9 | 17 | Die genannten schweren Probleme pauschal mit „NP-vollständig“ gleichgesetzt | Zwischen konkreten Entscheidungsvarianten differenziert; insbesondere ist planare 4-Färbung anders einzuordnen als 3-Färbung. |
| 10 | 29 | Bei NoSQL „verteilt über mehrere Server“ als festes Merkmal | „**können** auf mehrere Server verteilt sein“: Verteilung ist möglich, aber nicht zwingend. |
| 11 | 35 | „Personenbezogene Daten in AI-Tools verstoßen gegen Datenschutz“ | Auf **unzulässige Verarbeitung oder Eingabe** eingegrenzt; die Nutzung personenbezogener Daten ist nicht pauschal verboten. |

## Redaktionelle und technische Änderungen

| Nr. | Änderung |
|---|---|
| 12 | Word-Datei vollständig nach GitHub-kompatiblem Markdown (`.md`) übertragen; Textabschnitte und Tabellen übernommen. |
| 13 | Word-Deckblatt und statisches Inhaltsverzeichnis mit Seitenzahlen durch Markdown-Titelseite und verlinkte Kapitelübersicht ersetzt. Seitenzahlen werden in Markdown nicht fest vorgegeben. |
| 14 | Drucklayout, Seitenumbrüche und dekorative Word-Elemente nicht übernommen; sie werden in GitHub nicht benötigt. |
| 15 | Exportartefakte (z. B. Word-Listenmarker und HTML-Kommentare) bereinigt; Gliederung als Markdown-Überschriften dargestellt. |
| 16 | Den ursprünglichen Autor und die ursprüngliche KI-Nutzungserklärung beibehalten; die nachträgliche Bearbeitung im neuen Vorspann ausdrücklich kenntlich gemacht. |
| 17 | Im Quellenverzeichnis einen separaten Abschnitt für **zusätzliche Quellen der Korrekturfassung** ergänzt. Ursprüngliche Quellenangaben bleiben erhalten. |

**Hinweis:** Überarbeitet wurden die oben aufgeführten Stellen; dies ist keine vollständige inhaltliche Neuverifikation aller 47 Originalseiten oder aller externen Kursquellen. Rechtliche Fristen und Schwellenwerte des Kapitels 7 wurden in dieser Fassung unverändert aus dem Lernguide übernommen.
