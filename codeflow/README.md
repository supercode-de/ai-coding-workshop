# **Projekt: User Card Evolution**

Ein Web-Projekt zur Gestaltung einer **User Card**, die schrittweise optisch verbessert wird.

---

## **Feature-Liste & Implementierungsplan**

### **Ticket 1: HTML-Grundstruktur mit allen Inhalten erstellen**

**Ziel:** Alle benötigten Informationen in die HTML-Datei aufnehmen.

**Anforderungen:**

- Eine `div`-Box mit der Klasse `.card`, die die gesamte User Card umschließt.
- Zwei Unterbereiche:
  - `.card-left` für das Profilbild.
  - `.card-right` für Name, Standort und Kontakt.
- Ein Profilbild wird angezeigt. (https://randomuser.me/api/portraits/women/70.jpg)
- Eine Überschrift für den Namen.
- Ein Absatz für den Standort.
- Ein Link für die Kontaktaufnahme per E-Mail.

> Die Box hat noch **kein Styling** und erscheint in der Standard-Browser-Darstellung.

---

### **Ticket 2: Grundlegendes CSS für die User Card**

**Ziel:** Die User Card wird sichtbar und in eine Grundstruktur gebracht.

**Anforderungen:**

- Die `.card` bekommt eine feste **Breite und Höhe**.
- Eine **sichtbare Umrandung** wird hinzugefügt.
- `display: flex;` wird genutzt, um `.card-left` und `.card-right` nebeneinander anzuordnen.
- Standard-Schriftart setzen.
- `margin` und `padding` anpassen, um den Inhalt besser auszurichten.

> Die Karte ist nun sichtbar, aber noch ohne Farben und Feinheiten.

---

### **Ticket 3: Profilbild sichtbar und richtig positionieren**

**Ziel:** Das Profilbild soll korrekt angezeigt werden.

**Anforderungen:**

- Die `img`-Größe in `.card-left` auf 100px x 100px begrenzen.

---

### **Ticket 4: Erste Farbgestaltung ohne Variablen**

**Ziel:** Die Karte soll erste Farben erhalten.

**Anforderungen:**

- Eine Hintergrundfarbe für `.card` setzen.
- Die Schriftfarbe für `.card-right` anpassen.
- Eine Kontrastfarbe für den Kontakt-Link.

---

### **Ticket 5: Abrundungen und Schatten hinzufügen**

**Ziel:** Die Box wirkt weicher und plastischer.

**Anforderungen:**

- Von `.card` die Ecken abrunden.
- Schatten hinzufügen, um der Karte Tiefe zu geben.

---

### **Ticket 6: Profilbild abrunden & umrahmen**

**Ziel:** Das Bild soll sich besser ins Design einfügen.

**Anforderungen:**

- Das Bild soll rund erscheinen.
- Einen Rahmen um das Bild setzen.

---

### **Ticket 7: Typografie & Layout verfeinern**

**Ziel:** Die Lesbarkeit und das Layout optimieren.

**Anforderungen:**

- `h2`, `p` und `a` bekommen verbesserte Schriftgrößen.
- Textfarben besser auf den Hintergrund abstimmen.
- Abstände (`margin`, `padding`) für eine bessere Ausrichtung anpassen.

---

### **Ticket 8: Semantische HTML-Tags einführen**

**Ziel:** Die Struktur der HTML-Datei verbessern.

**Anforderungen:**

- `div` Element durch semtantische HTML5 Elemente ersetzen
- Name als `h2`, Standort als `p` und Kontakt als `a` können bleiben

> Optisch bleibt alles gleich, aber die Struktur wird sauberer.

---

### **Ticket 9: Einführung von Farbvariablen**

**Ziel:** Das Styling flexibler und anpassbarer machen.

**Anforderungen:**

- Eine zentrale **Farbpalette** im `:root` definieren.
- Alle bisherigen festen Farben durch **CSS-Variablen** ersetzen.

---

### **Ticket 10: Hintergrund der Seite verbessern**

**Ziel:** Der gesamte Hintergrund der Seite soll sich dem Design der Karte anpassen.

**Anforderungen:**

- Ein Farbverlauf für den `body`-Hintergrund.
- Die `.card`-Hintergrundfarbe leicht transparent machen.

---

### **Ticket 11: Button-Design verbessern**

**Ziel:** Der Kontakt-Button soll sich optisch besser einfügen.

**Anforderungen:**

- **Abgerundete Ecken** für den Button.
- **Hover-Effekt**, der Farbe oder Schatten verändert.
