# Projekt: Click Counter App

Ein einfaches Web-App-Projekt, bei dem ein Button geklickt wird, um einen Zähler zu erhöhen.

## Feature-Liste & Implementierungsplan

### Ticket 1: Grundlegende HTML-Struktur

**Ziel:** Die Basisstruktur der HTML-Seite erstellen.

**Anforderungen:**

- Ein `<h1>`-Titel für die App.
- Ein `<p>`-Element, das den aktuellen Zählerstand (beginnend bei 0) anzeigt.
- Ein `<button>`-Element mit der Beschriftung **"increment"**.

---

### Ticket 2: Grundlegendes Styling (CSS)

**Ziel:** Die Seite optisch ansprechend gestalten.

**Anforderungen:**

- Der Zählertext soll eine größere Schrift haben.
- Der Button soll mit Padding, einem Border und einem Hover-Effekt gestaltet sein.
- Die Seite soll eine Hintergrundfarbe haben.

---

### Ticket 3: Zähler-Funktionalität (JavaScript)

**Ziel:** Interaktivität mit JavaScript hinzufügen.

**Anforderungen:**

- JavaScript schreiben, um den Zähler bei jedem Klick zu erhöhen.
- Der aktualisierte Wert soll im `<p>`-Element angezeigt werden.
- Der Zähler soll bei **0** starten.

---

## Zusätzliche Feature-Tickets

### Ticket 4: Reset-Button hinzufügen

**Ziel:** Nutzern ermöglichen, den Zähler auf Null zurückzusetzen.

**Anforderungen:**

- Einen zweiten Button mit der Beschriftung **"Reset"** hinzufügen.
- Beim Klicken auf den **"Reset"**-Button soll der Zähler auf 0 gesetzt werden.

---

### Ticket 5: Decrement-Button hinzufügen

**Ziel:** Nutzern ermöglichen, den Zähler zu verringern.

**Anforderungen:**

- Einen neuen Button mit der Beschriftung **"Decrement"** hinzufügen.
- Beim Klicken soll der Zähler um **1** reduziert werden.
- Der Zähler darf **nicht unter 0** fallen.

---

### Ticket 6: Schrittweite anpassbar machen

**Ziel:** Nutzern erlauben, die Schrittweite für die Erhöhung/Verringerung des Zählers zu bestimmen.

**Anforderungen:**

- Ein `<input>`-Feld hinzufügen, in das Nutzer eine Schrittweite eingeben können.
- Der Button soll den Zähler um diesen Wert erhöhen oder verringern.
- **Standardwert:** 1.

---

### Ticket 7: Light/Dark-Mode umschalten

**Ziel:** Nutzern erlauben, zwischen einem hellen und dunklen Modus zu wechseln.

**Anforderungen:**

- Einen Toggle-Button **"Dark Mode"** hinzufügen.
- Beim Klicken soll zwischen hellen und dunklen Farben gewechselt werden.

---

### Ticket 8: Animierte Zähler-Textanzeige

**Ziel:** Beim Erhöhen/Verringern des Zählers soll eine Animation stattfinden.

**Anforderungen:**

- Eine **Fade-in- oder Bounce-Animation** auf das Zähler-Element anwenden.
- Die Animation soll nur bei Zahlenänderung stattfinden.

---

### Ticket 9: Fortschrittsbalken für Klicks hinzufügen

**Ziel:** Nutzer visuell über den Fortschritt der Klicks informieren.

**Anforderungen:**

- Einen **horizontalen Fortschrittsbalken** unter dem Zähler anzeigen.
- Der Balken füllt sich mit zunehmender Klickzahl.
- **Maximalwert:** 100 Klicks.
