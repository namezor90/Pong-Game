# 🏓 Pong Game

[![Python](https://img.shields.io/badge/Python-3.8%2B-blue.svg)](https://www.python.org/downloads/)
[![License](https://img.shields.io/badge/License-MIT-green.svg)](LICENSE)

Klasszikus Pong játék újraalkotva Python Turtle grafikával. Versenyezz barátod ellen ebben az időtlen arcade játékban!

## ✨ Jellemzők

- 🎮 2 játékos mód
- 📊 Pontozási rendszer
- 🎨 Retró kinézet
- 🏃 Dinamikus labdasebesség
- 💥 Ütközésérzékelés
- 🔄 Folyamatos játékmenet

## 🚀 Telepítés

```bash
git clone https://github.com/namezor90/pong-game.git
cd pong-game
python main.py
```

## 💻 Használat

### Bal oldali játékos:
- ⬆️ Fel nyíl: Felfelé mozgás
- ⬇️ Le nyíl: Lefelé mozgás

### Jobb oldali játékos:
- `W`: Felfelé mozgás
- `S`: Lefelé mozgás

## 📁 Projekt Struktúra

```
pong-game/
├── main.py       # Fő játék logika
├── paddle.py     # Ütő osztály
├── ball.py       # Labda osztály
└── scoreboard.py # Pontszám kezelés
```

## 🎯 Játékszabályok

- A labda folyamatosan pattog a pályán
- Az ütőkkel kell eltalálni a labdát
- Pont szerzése ha az ellenfél elmulasztja a labdát
- A labda gyorsul minden ütközésnél
- A játék végtelenig tart, vagy amíg ki nem lépsz

## 🛠️ Fejlesztés

A játék testreszabható a következő paraméterekkel:
```python
# Labda beállítások
self.move_speed = 0.1  # Kezdő sebesség
self.x_move = 10      # Vízszintes mozgás
self.y_move = 10      # Függőleges mozgás

# Ütő beállítások
stretch_wid = 5       # Ütő magassága
stretch_len = 1       # Ütő szélessége
```

## 📝 Licensz

[MIT](LICENSE)

## 🤝 Közreműködés

1. Fork-old a projektet
2. Hozz létre egy új branch-et (`git checkout -b feature/awesome`)
3. Commit-old a változtatásokat (`git commit -m 'Add awesome feature'`)
4. Push-old a branch-et (`git push origin feature/awesome`)
5. Nyiss egy Pull Request-et

## 👥 Szerzők

- [@namezor90](https://github.com/namezor90)

## 🎮 Jövőbeli fejlesztési lehetőségek

- 🏆 Győztes hirdetése adott pontszámnál
- 🎵 Retró hangeffektek
- 🌈 Színes labda és ütők
- 🏁 Különböző nehézségi szintek
- 💫 Power-up-ok és speciális képességek
- 🤖 Egyjátékos mód AI ellenféllel
- 📱 Érintőképernyős támogatás
