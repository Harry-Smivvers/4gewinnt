# Connect Four — 4 Gewinnt

> **Play directly in your browser — no installation, no dependencies, one single HTML file.**

A polished, fully responsive **Connect Four** game with a smart AI opponent powered by **Minimax with Alpha-Beta Pruning**. Works great on desktop, laptop, and mobile.

---

## English

### Features

- **Single-file app** — just open `connect-four.html` in any modern browser
- **Smart AI** — Minimax algorithm with alpha-beta pruning and configurable search depth
- **Responsive design** — adapts to any screen size, from desktop to smartphone
- **Full keyboard control** — play without touching the mouse
- **Smooth animations** — stones drop with a satisfying physics-like bounce
- **Win detection** — winning four are highlighted on the board
- **Menu overlay** — change AI difficulty mid-game without restarting

---

### How to Play

#### Setup Screen

| Option | Description |
|---|---|
| **Your Color** | Choose Red or Yellow |
| **Who Goes First** | You or the Computer |
| **Minimax Depth** | AI difficulty level (see below) |

Click **Start Game** to begin.

---

### Keyboard Controls

#### Setup Screen

| Key | Action |
|---|---|
| `Arrow Down` / `Arrow Right` | Move focus to next option |
| `Arrow Up` / `Arrow Left` | Move focus to previous option |
| `Enter` | Activate selected option / confirm depth input |
| `Escape` | Cancel depth editing |

#### In-Game

| Key | Action |
|---|---|
| `Arrow Left` | Move column selector left |
| `Arrow Right` | Move column selector right |
| `Enter` or `Space` | Drop stone in selected column |
| `Arrow Up` | Open in-game menu |

#### Result Screen

| Key | Action |
|---|---|
| `Arrow Left` / `Arrow Right` | Switch between Play Again / Main Menu |
| `Enter` | Confirm selection |

#### In-Game Menu

| Key | Action |
|---|---|
| `Arrow Up` / `Arrow Down` | Navigate menu items |
| `Enter` | Select item |
| `Escape` | Close menu |

---

### AI Difficulty — Minimax Depth

The AI uses the **Minimax algorithm** with **alpha-beta pruning**. The depth setting controls how many moves ahead the AI looks.

| Depth | Strength | Speed |
|---|---|---|
| 1 – 2 | Beginner | Instant |
| 3 – 4 | Easy | Very fast |
| **5** | **Medium (default)** | **Fast** |
| 6 – 7 | Hard | Noticeable delay |
| 8+ | Very Hard | Slow on older devices |

**Tip:** Depth 5 is the sweet spot — strong enough to challenge most players, fast enough to feel responsive. For a real challenge, try depth 7 or 8.

The depth can also be changed **during a running game** via the in-game menu (`Arrow Up` key).

---

### Playing on Mobile

The game is fully touch-friendly:

- **Tap any cell** in a column to drop your stone there
- The board automatically scales to fit your screen
- Column selector arrows and hover highlights adjust for touch devices
- No pinch-zoom required — everything fits in the viewport
- Works in any mobile browser (Chrome, Safari, Firefox) — no app needed

**Tip:** Add the page to your home screen for a full-screen experience.

---

### Quick Start

```bash
# Clone and open — that's it
git clone https://gitlab.com/yourname/connect-four.git
cd connect-four
open connect-four.html   # macOS
start connect-four.html  # Windows
xdg-open connect-four.html  # Linux
```

Or simply [download the HTML file](connect-four.html) and double-click it.

---

---

## Deutsch

> **Direkt im Browser spielen — keine Installation, keine Abhängigkeiten, eine einzige HTML-Datei.**

Ein ansprechendes, vollständig responsives **4-Gewinnt-Spiel** mit einem cleveren KI-Gegner auf Basis von **Minimax mit Alpha-Beta-Pruning**. Funktioniert perfekt auf Desktop, Laptop und Smartphone.

---

### Funktionen

- **Single-File-App** — `connect-four.html` einfach in einem modernen Browser öffnen
- **Intelligente KI** — Minimax-Algorithmus mit Alpha-Beta-Pruning und einstellbarer Suchtiefe
- **Responsives Design** — passt sich jeder Bildschirmgröße an, vom Desktop bis zum Smartphone
- **Vollständige Tastatursteuerung** — ohne Maus spielen
- **Flüssige Animationen** — Steine fallen mit einem angenehmen physikalischen Abprallen
- **Gewinnmarkierung** — die siegreichen vier Steine werden auf dem Spielfeld hervorgehoben
- **Menü-Overlay** — KI-Schwierigkeit während des Spiels ändern, ohne neu zu starten

---

### Spielanleitung

#### Startbildschirm

| Option | Beschreibung |
|---|---|
| **Deine Farbe** | Rot oder Gelb wählen |
| **Wer beginnt?** | Du oder der Computer |
| **Minimax-Tiefe** | KI-Schwierigkeitsstufe (siehe unten) |

Auf **Start Game** klicken, um zu beginnen.

---

### Tastatursteuerung

#### Startbildschirm

| Taste | Aktion |
|---|---|
| `Pfeil unten` / `Pfeil rechts` | Fokus zur nächsten Option |
| `Pfeil oben` / `Pfeil links` | Fokus zur vorherigen Option |
| `Enter` | Ausgewählte Option aktivieren / Tiefeneingabe bestätigen |
| `Escape` | Tiefeneingabe abbrechen |

#### Im Spiel

| Taste | Aktion |
|---|---|
| `Pfeil links` | Spaltenauswahl nach links |
| `Pfeil rechts` | Spaltenauswahl nach rechts |
| `Enter` oder `Leertaste` | Stein in ausgewählte Spalte werfen |
| `Pfeil oben` | In-Game-Menü öffnen |

#### Ergebnisbildschirm

| Taste | Aktion |
|---|---|
| `Pfeil links` / `Pfeil rechts` | Zwischen „Play Again" / „Main Menu" wechseln |
| `Enter` | Auswahl bestätigen |

#### In-Game-Menü

| Taste | Aktion |
|---|---|
| `Pfeil oben` / `Pfeil unten` | Zwischen Menüpunkten navigieren |
| `Enter` | Punkt auswählen |
| `Escape` | Menü schließen |

---

### KI-Schwierigkeit — Minimax-Tiefe

Die KI verwendet den **Minimax-Algorithmus** mit **Alpha-Beta-Pruning**. Die Tiefeneinstellung bestimmt, wie viele Züge die KI vorausberechnet.

| Tiefe | Stärke | Geschwindigkeit |
|---|---|---|
| 1 – 2 | Anfänger | Sofort |
| 3 – 4 | Leicht | Sehr schnell |
| **5** | **Mittel (Standard)** | **Schnell** |
| 6 – 7 | Schwer | Spürbare Verzögerung |
| 8+ | Sehr schwer | Langsam auf älteren Geräten |

**Tipp:** Tiefe 5 ist der ideale Mittelwert — stark genug, um die meisten Spieler zu fordern, schnell genug für ein flüssiges Spielgefühl. Für eine echte Herausforderung Tiefe 7 oder 8 ausprobieren.

Die Tiefe kann auch **während eines laufenden Spiels** über das In-Game-Menü geändert werden (Taste `Pfeil oben`).

---

### Auf dem Smartphone spielen

Das Spiel ist vollständig touch-freundlich:

- **Auf eine beliebige Zelle tippen**, um den Stein in die entsprechende Spalte zu werfen
- Das Spielfeld skaliert automatisch auf die Bildschirmgröße
- Spaltenauswahl-Pfeile und Hover-Hervorhebungen passen sich Touch-Geräten an
- Kein Pinch-Zoom nötig — alles passt in den Viewport
- Funktioniert in jedem mobilen Browser (Chrome, Safari, Firefox) — keine App erforderlich

**Tipp:** Die Seite zum Home-Bildschirm hinzufügen für ein Vollbild-Erlebnis.

---

### Schnellstart

```bash
# Klonen und öffnen — das war's
git clone https://gitlab.com/yourname/connect-four.git
cd connect-four
open connect-four.html   # macOS
start connect-four.html  # Windows
xdg-open connect-four.html  # Linux
```

Oder einfach die [HTML-Datei herunterladen](connect-four.html) und per Doppelklick öffnen.

---

## License / Lizenz

MIT — free to use, modify, and share.
