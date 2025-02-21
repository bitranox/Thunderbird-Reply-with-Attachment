# Antwort mit Anhängen

## ![US Flag](https://github.com/ashleedawg/flags/blob/master/US.png?raw=true) [Switch to English version](README.md)

**Reply with Attachments** ist ein offizielles Thunderbird-Add-on, das automatisch Anhänge aus der ursprünglichen E-Mail hinzufügt, wenn auf eine Nachricht geantwortet wird. SMIME-Zertifikate werden dabei ausgeschlossen.

---

## Funktionen

- Fügt beim Antworten automatisch Anhänge aus der ursprünglichen E-Mail hinzu.
- Überspringt SMIME-Zertifikate, um unnötige Anhänge zu vermeiden.

Screenshot, der die Erweiterung in Aktion zeigt:

![Reply with Attachments Screenshot](screenshot.png)

---

## Installation - in Thunderbird (Empfohlene Methode)
1. in Thunderbird gehe zu Gehe zu **Extras > Add-ons und Themes** uns suche nach "reply with attachments"
2. füge das Addon hinzu

---

## Installation - PRIVATE - von der offiziellen Add-on-Page (für Entwicklung)

### Schritt 1: XPI-Datei herunterladen
1. Gehe zu [Thunderbird Add-on Seite](https://addons.thunderbird.net/de/thunderbird/search/?q=reply%20with%20attachments)
2. Lade die neueste Version des Add-ons als XPI-Datei herunter (`reply_with_attachments-x.y.z-tb.xpi`).

### Schritt 2: Installation in Thunderbird
1. Öffne Thunderbird.
2. Gehe zu **Extras > Add-ons und Themes**.
3. Klicke im **Add-ons-Manager** auf das Zahnrad-Symbol oben rechts.
4. Wähle im Dropdown-Menü **Add-on aus Datei installieren...**.
5. Wähle die heruntergeladene Datei `reply_with_attachments-x.y.z-tb.xpi` aus.
6. Bestätige die Installation, wenn du dazu aufgefordert wirst.

---

## Installation - PRIVATE - letzte Version von Github (für Entwicklung)

### Schritt 1: ZIP-Datei herunterladen
1. Gehe zum Bereich [Releases](https://github.com/bitranox/Thunderbird-Reply-with-Attachment/releases) dieses Repositorys.
2. Lade die neueste Version des Add-ons als ZIP-Datei herunter (`reply-with-attachments-plugin-PRIVATE.zip`)

### Schritt 2: Installation in Thunderbird
1. Öffne Thunderbird.
2. Gehe zu **Extras > Add-ons und Themes**.
3. Klicke im **Add-ons-Manager** auf das Zahnrad-Symbol oben rechts.
4. Wähle im Dropdown-Menü **Add-on aus Datei installieren...**.
5. Wähle die heruntergeladene Datei `reply-with-attachments-plugin-PRIVATE.zip` aus.
6. Bestätige die Installation, wenn du dazu aufgefordert wirst.

---

## Verwendung

1. Öffne eine E-Mail in Thunderbird.
2. Klicke auf **Antworten** oder **Allen antworten**.
3. Das Add-on fügt automatisch alle Anhänge der ursprünglichen E-Mail in die Antwort ein.
4. SMIME-Zertifikate werden übersprungen.

---

## Kompatibilität

- **Getestet mit Thunderbird Nebula 128.6.0esr (64-Bit).**
- **Ältere Thunderbird-Versionen werden nicht unterstützt.**

---

## Fehlerbehebung

- Wenn das Add-on nicht wie erwartet funktioniert, stelle sicher, dass du eine kompatible Version von Thunderbird verwendest (128.6.0esr oder neuer).
- Überprüfe die Fehlerkonsole von Thunderbird (**Extras > Entwicklerwerkzeuge > Fehlerkonsole**) auf Probleme, die mit dem Add-on zusammenhängen.

---

## Mitwirken

Wenn du zu diesem Projekt beitragen möchtest:
1. Forke das Repository.
2. Erstelle einen Feature-Branch (`git checkout -b feature-name`).
3. Committe deine Änderungen (`git commit -m "Add feature name"`).
4. Pushe deinen Branch (`git push origin feature-name`).
5. Öffne einen Pull-Request.

---

## Unterstütze dieses Projekt

Wenn dir dieses Add-on gefällt, unterstütze die Entwicklung mit einem kleinen Beitrag:

[![Spenden via PayPal](https://raw.githubusercontent.com/stefan-niedermann/paypal-donate-button/master/paypal-donate-button.png)](https://www.paypal.com/donate/?hosted_button_id=7KJN33DHTA8WE)

---

## Lizenz

Dieses Projekt ist unter der GNU General Public License v3 lizenziert.  
Den vollständigen Lizenztext findest du [hier](https://github.com/bitranox/Thunderbird-Reply-with-Attachments/blob/master/LICENCE).

---

## Danksagungen

Vielen Dank an die Thunderbird-Add-on-Entwickler-Community für die hervorragende Dokumentation und Unterstützung.

--- 

## Versionsverlauf / Changelog

### V1.0.1
- Ersetzte die benutzerdefinierte Funktion `getAttachmentsFromMessage()`, die die MIME-Teile manuell durchlief, durch die Standardmethode `browser.messages.listAttachments()`.

### V1.0.0
- Erste Veröffentlichung.

