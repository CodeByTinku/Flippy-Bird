# 🐦 Flippy Bird Game

A simple **Flappy Bird clone** built using **HTML, CSS, and JavaScript (Canvas API)**.  
The game includes smooth physics, pipe obstacles, scoring system, and background music for an engaging experience.

---

## 🎮 Features
- ✨ Built with **HTML, CSS, and JavaScript** (no external libraries)  
- 🎵 Background music (`bgm_mario.mp3`) with loop support  
- 🐦 Bird physics with gravity and jump mechanics  
- 🚧 Randomly generated pipes with collision detection  
- 📊 Score tracking system  
- 🔄 Game reset on collision or fall  
---
## 🚀 Demo
🎯 **Live Demo**: [Play Here](https://flippy-bird-livid.vercel.app/)
---
```
## 📂 Project Structure
flippy-bird/
│── index.html
│── style.css
│── script.js
│── flappybird.png
│── toppipe.png
│── bottompipe.png
│── bgm_mario.mp3
```
---

## ⚙️ How to Play
1. Clone or download this repository  
2. Open `index.html` in your browser  
3. Press **Space**, **Arrow Up**, or **X** to make the bird jump  
4. Avoid hitting the pipes or falling down  
5. Try to score as high as possible!
---
## 🛠️ Code Highlights
- **Canvas Rendering**: Used `context.drawImage()` for bird and pipes  
- **Physics**: Gravity (`0.4`) and jump velocity (`-6`)  
- **Collision Detection**: Axis-Aligned Bounding Box (AABB) method  
- **Game Loop**: `requestAnimationFrame(update)` for smooth animation

## 🚀 Future Improvements
- Add difficulty levels  
- Mobile touch controls  
- High score saving using LocalStorage  
- Animated background 
