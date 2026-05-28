# 🎮 SpielePortal

Eine moderne **Single-File** HTML5 Spiele Website mit 5 Kategorien – wie Poki.

Einfach die `index.html` öffnen und sofort spielen. Kein Server nötig!

---

## ✨ Features

- 5 Kategorien: Arcade, Puzzle, Racing, Action, Adventure
- Über 50 fertige HTML5 Spiele
- Schöner Vollbild-Modus mit Zurück-Button
- Suchfunktion
- Kategorie-Filter
- ESC-Taste zum Schließen
- Voll responsiv (Handy + PC)
- Nur **eine** Datei

---

## 🚀 So starten

1. Die `index.html` herunterladen
2. Datei im Browser öffnen (Chrome empfohlen)
3. Spielen!

---

## 📁 Dateien

- `index.html` → Die komplette Website (alles in einer Datei)

---

## 🎯 Kategorien & Spiele

**Arcade** – Flappy Bird, Snake, Subway Surfers, Pac-Man, Temple Run usw.  
**Puzzle** – 2048, Tetris, Sudoku, Candy Crush, Wordle usw.  
**Racing** – Highway Racer, Moto X3M, Drift Racing usw.  
**Action** – Stickman Hook, Krunker.io, Rooftop Snipers usw.  
**Adventure** – Mario, Sonic, Minecraft Classic, Happy Wheels usw.

---

## 🛠 Neue Spiele hinzufügen

Öffne `index.html` und ergänze im `games` Array neue Einträge:

```javascript
{
  title: "Spiel Name",
  theme: "Arcade",
  thumbnail: "https://picsum.photos/id/1015/300/160",
  url: "https://link-zum-spiel.de"
},
