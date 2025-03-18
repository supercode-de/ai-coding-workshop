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

## **Ticket 2: Grundlegendes CSS für die User Card hinzufügen**

**Ziel:** Die Karte sichtbar machen und die Struktur mit `display: flex` aufbauen.

### **Anforderungen:**

- `.card` bekommt eine feste **Breite (600px) und Höhe (200px)**.
- Eine **sichtbare Umrandung** wird hinzugefügt.
- Die Elemente `.card-left` und `.card-right` werden **nebeneinander** angeordnet.
- Eine Standard-Schriftart wird gesetzt.

---

## **Ticket 3: Profilbild und rechte Seite richtig positionieren**

**Ziel:** Das Profilbild korrekt anzeigen und die rechte Seite (`.card-right`) ausrichten.

### **Anforderungen:**

- `.card-left` nimmt **50 % der Breite** ein.
- `.card-left` wird mit `display: flex` ausgestattet.
- Das Profilbild (`img`) bekommt eine feste Größe von **100px x 100px**.
- Das Bild wird **zentriert ausgerichtet**.
- `.card-right` nimmt ebenfalls **50 % der Breite** ein.
- `.card-right` wird mit `display: flex`, `flex-direction: column` und `align-items: center` ausgerichtet.

---

### **Ticket 4: Erste Farbgestaltung**

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
