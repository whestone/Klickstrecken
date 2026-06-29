# Klickstrecken

Ein webbasiertes Tool, das Arbeitsprozesse in klickbare Strecken verwandelt.
Jeder Schritt stellt eine Frage oder gibt eine Anweisung, jede Antwort führt
zum nächsten Schritt – bis zum richtigen Ergebnis.

## Nutzung

Es ist keine Installation und kein Build nötig – das Tool ist eine einzige,
in sich geschlossene HTML-Datei.

- **Direkt:** `index.html` per Doppelklick im Browser öffnen.
- **Über einen lokalen Server** (optional, z. B. für mobile Tests):

  ```bash
  npx -y vite --port 5180
  ```

## Funktionen

- **Bearbeiten** – Schritte anlegen/löschen, Antworten mit Folgeschritten
  verknüpfen, Startschritt festlegen.
- **Durchklicken** – durch den Prozess klicken; die zurückgelegte Klickstrecke
  läuft als Breadcrumb mit, inklusive Zurück- und Neu-starten-Funktion.
- **Mehrere Klickstrecken** in der Seitenleiste verwalten.
- **Automatische Speicherung** im Browser (localStorage).
- **Export / Import** als JSON zum Teilen und Sichern.

## Technik

Vanilla HTML/CSS/JavaScript, keine Abhängigkeiten, kein Build-Schritt.
