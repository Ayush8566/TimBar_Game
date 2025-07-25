# 🌲 Timber Game (C++ with SFML)

A fun arcade-style game where you chop trees as fast as you can—before time runs out or a branch crushes you! Built with **C++** and **SFML**.

---

## 📸 Gameplay Preview

> 🔨 Press Left or Right to chop the tree. Avoid getting squished by falling branches!

---

## 🎮 Controls

| Key        | Action              |
|------------|---------------------|
| `Enter`    | Start/Restart Game  |
| `← Left`   | Chop from Left side |
| `→ Right`  | Chop from Right side|
| `Esc`      | Exit Game           |

---

## 🛠️ Requirements

- C++ compiler (g++, clang++, MSVC)
- [SFML 2.5+](https://www.sfml-dev.org/download.php)
- Game assets placed in `graphics/` and `fonts/` folders.

---

## 🚀 Build Instructions

### With g++

```bash
g++ -o timber timber.cpp -lsfml-graphics -lsfml-window -lsfml-system
./timber


📦 timber-game/
├── timber.cpp
├── README.md
├── graphics/
│   ├── background.png
│   ├── tree.png
│   ├── bee.png
│   ├── cloud.png
│   ├── player.png
│   ├── axe.png
│   ├── log.png
│   ├── rip.png
│   └── branch.png
├── fonts/
│   └── KOMIKAP_.ttf



---

Let me know if you want this uploaded into a ready-made GitHub repo or zipped folder with everything. I can also help with the `CMakeLists.txt` or GitHub Pages deployment.

