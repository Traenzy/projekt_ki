**Laborarbeit Künstliche Intelligenz**

**Thema:**
Constraint Satisfaction Problems

**Problemstellung: Belegung von Laboren für Projektpräsentationen**

An einer Hochschule soll der Präsentationsplan für die Projektwoche mehrerer Studiengänge
erstellt werden. In dieser Woche stehen insgesamt drei Laborräume zur Verfügung, bezeichnet
als L1, L2 und L3. Die Woche umfasst fünf Tage von Montag bis Freitag, und jeder dieser Tage
besitzt vier feste Präsentationszeiten: einen ersten Slot von 8:00 bis 9:00 Uhr, einen zweiten
Slot von 10:00 bis 11:00 Uhr, einen dritten Slot von 13:00 bis 14:00 Uhr und einen vierten Slot
von 15:00 bis 16:00 Uhr.
Jeder Studiengang hat eine bestimmte Anzahl an Projektgruppen. Jede Projektgruppe muss
genau drei Präsentationen innerhalb dieser Woche halten, und jede dieser Präsentationen
muss einem eindeutigen Tages-Slot-Raum-Termin zugewiesen werden. Natürlich können sich
weder Prüflingen noch Prüfungskommission zeitlich und räumlich „zerreißen“ und parallele
Termine wahrnehmen, auch kann in einem Raum immer nur eine Präsentation laufen.
Zu jedem Studiengang gehören weiterhin eine bis drei Prüfungskommissionen, die
ausschließlich die Projektgruppen ihres eigenen Studiengangs betreuen. Jede Präsentation
einer Projektgruppe muss genau einer der Kommissionen ihres Studiengangs zugeordnet
werden.
Für die zeitliche Lage der Präsentationen jeder einzelnen Projektgruppe gilt eine zusätzliche
Bedingung: Wenn eine Gruppe an einem Tag die Präsentation im vierten Slot (15:00–16: 00
Uhr) hält, dann darf dieselbe Gruppe am unmittelbar nächsten Tag nicht im ersten Slot (8:00–
9: 0 0 Uhr) präsentieren.
Auch für die Prüfungskommissionen gibt es eine wichtige organisatorische Einschränkung:
Eine Kommission darf an einem einzelnen Tag höchstens einmal den Raum wechseln.
Alle Präsentationen der gesamten Woche müssen also vollständig und konflikfrei in das
Schema aus fünf Tagen, vier Slots pro Tag und drei Räumen eingeplant werden. Damit besteht
die Aufgabe darin, für jede der benötigten Präsentationen eine Kombination aus Tag, Slot,
Raum und Kommission zu finden, sodass alle oben genannten Bedingungen gleichzeitig erfüllt
werden. Sollte das nicht möglich sein ist dies zu begründen. Zusätzliches, weiches Constraint:
Prüfungskommissionen sollten an einem Tag nicht länger als nötig im Haus gehalten werden,
d.h. wenn ein früherer Präsentationsslot möglich ist, so ist dieser zu nutzen.

Die Daten zur individuellen Aufgabenstellung werden separat zugeteilt.


**Aufgabenstellung:**

Entwerfen Sie ein KI Modell auf Basis von Constraints und setzen Sie dieses als Jupyter
Notebook um. Wählen Sie geeignete Constraints.

Erläutern und begründen Sie dazu auch kurz Ihre jeweilige Konfiguration. Testen Sie die
Lösungen und ggf. verschiedene Parametrisierungen und bewerten Sie diese.

**Bewertungskriterien**

_Fachliche Bearbeitung (20 Punkte)_
Lösungsqualität und Umsetzung der Funktionalität / korrekte Verwendung von
Kernfunktionen der jeweiligen KI Methoden/ Anpassung an die Aufgabenstellung / Nutzung
der erworbenen Kenntnisse aus der Vorlesung.

_Dokumenta9on und Reflexion (30 Punkte)_
Begründung von Entwurf und Umsetzung, Begründung und Bewertung der Unterschiede /
Vergleich der Verfahren, Test und Ergebnisbewertung / Codequalität und Dokumentation

**Abgabe**

Datum: **19.12.**
Abzugeben: Jupyter Notebook mit Quellcode und Dokumentation
Einzureichen über das Moodle Lernsystem.

_Hinweis:_

Die Nutzung der in der Vorlesung durchgeführten Labore und zugehörigen Lösungen ist
zulässig


