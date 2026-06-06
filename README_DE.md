# Gothic Remake – Schloss-Knacker

Danke, dass ihr das Tool heruntergeladen habt! 🏰

---

## Was ist das?

Gothic Remake hat ein Schloss-Knack-Minispiel, bei dem ihr 6 Riegel auf eine bestimmte Position bringen müsst. Das Knifflige daran: Viele Riegel sind miteinander verbunden und bewegen sich gegenseitig, wenn man sie drückt – das macht es schnell unübersichtlich. Dieses Tool berechnet automatisch die optimale Züge-Abfolge für jedes Schloss.

Ihr gebt die Startpositionen der Riegel und ihre Verbindungen untereinander ein, und das Tool sagt euch Schritt für Schritt genau, was zu drücken ist.

**Was das Tool kann:**
- Visuelle Anzeige der Riegelpositionen mit 7-Loch-Leiste
- Verbindungsmatrix für alle Verbindungstypen, die im Spiel vorkommen (keine Verbindung / entgegengesetzte Richtung / gleiche Richtung)
- Zwei Lösungsmodi: minimale Züge (BFS – minimiert die reine Anzahl der Riegeldrücke) und minimale Tastendrücke (Dijkstra – empfohlen, da intuitiver und für das tatsächliche Spielerlebnis optimiert)
- Schritt-für-Schritt-Tabelle, die genau angibt, welchen Riegel ihr drücken müsst und welche Taste dafür nötig ist

---

## Installation & Anleitung

Das Tool funktioniert als einfache HTML-Datei direkt im Browser – es muss nichts installiert werden.

**Schritt 1 – Datei öffnen**
Ladet `index-de.html` herunter und öffnet sie mit einem Doppelklick. Sie öffnet sich automatisch in eurem Browser (Chrome, Firefox, Edge – alles funktioniert).

**Schritt 2 – Startpositionen eintragen**
Schaut euch im Spiel an, auf welchem Loch (1–7) jeder der 6 Riegel gerade steht. Tragt das mit den ◀ ▶ Buttons ein. Das mittlere Loch (4) ist immer das Ziel – es ist grün markiert.

**Schritt 3 – Verbindungen konfigurieren**
Manche Riegel bewegen andere Riegel mit, wenn ihr sie drückt. Das seht ihr direkt im Spiel, wenn ihr einen Riegel bewegt. Klickt in der Verbindungsmatrix auf die entsprechende Zelle, um den Typ zu wählen – ein Klick wechselt durch die drei Möglichkeiten:
- **–** keine Verbindung
- **≠** der verbundene Riegel bewegt sich entgegengesetzt
- **=** der verbundene Riegel bewegt sich in gleicher Richtung

*(Zeile = der Riegel, den ihr bewegt, Spalte = der betroffene Riegel)*

**Schritt 4 – Lösung berechnen**
Wählt einen Modus – empfohlen ist **Min. Tastendrücke** – und klickt auf **Lösung berechnen**. Das Tool gibt euch eine Tabelle mit dem besten Lösungsweg aus.

---

Ich hoffe, dass euch das Tool ein bisschen das Leben erleichtert und ihr eure Truhen künftig etwas schneller knackt! ⚔️

Falls ihr mich ein wenig unterstützen wollt, freue ich mich sehr über einen Kaffee:
https://ko-fi.com/iblubbii – Vielen Dank! ☕

---

## Lizenz

MIT
