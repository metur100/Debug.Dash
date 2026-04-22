# 🐞 Debug Dash

> A fast-paced endless runner game by **RealCore Services GmbH**  
> Built with HTML5 Canvas · No dependencies · Pure JavaScript

---

## 🎮 What is Debug Dash?

**Debug Dash** is a browser-based endless runner where you play as a developer sprinting through a dark terminal world. Your mission: survive 60 seconds by jumping over bugs and grabbing coffee to keep your energy up — before your system crashes!

---

## 🕹️ How to Play

| Action | Control |
|---|---|
| Jump | `Click` / `Space` / `Arrow Up` |
| Restart | Click the **🔄 RESTART** button |

---

## ⚙️ Game Mechanics

### 🐛 Bugs
- Bugs spawn from the right side and move toward you
- **Jump over them** to avoid damage
- Getting hit costs you **-15 Energy**

### ☕ Coffee
- Coffee cups also spawn from the right
- **Run into them** (do NOT jump) to collect
- Each coffee restores **+20 Energy**

### 🔋 Energy System
- You start with **80% Energy**
- Energy drains **passively** over time (-0.25/sec)
- If Energy hits **0%** → Game Over 💀

### ⚡ Speed Ramp
- After **15 seconds**, the game gradually speeds up
- Maximum speed: **5.8x**

### 🏆 Win Condition
- Survive for **60 seconds** → **DEPLOY SUCCESS!** 🎉

---

## 📊 Stats Tracked

| Stat | Description |
|---|---|
| 💻 Score | Points earned over time |
| 🔋 Energy | Current energy level (%) |
| 🐛 Bugs Hit | Total bugs you collided with |
| ☕ Coffee | Total coffee cups collected |

---

## 🚀 How to Run

1. Download or clone the project
2. Open `DebugDash_Fixed.html` in any modern browser
3. Click the canvas or press `Space` to start jumping
4. Survive 60 seconds — good luck! 🤞

> ✅ No installation required. No npm. No build step. Just open and play.

---

## 🗂️ File Structure

```
DebugDash/
└── DebugDash_Fixed.html    ← The entire game (single file)
```

---

## 🛠️ Tech Stack

| Technology | Usage |
|---|---|
| HTML5 Canvas | Game rendering |
| Vanilla JavaScript | Game logic & physics |
| CSS3 | UI styling & layout |
| Monospace / Courier New | Terminal aesthetic font |

---

## 💡 Tips & Tricks

- 🎯 **Timing is everything** — don't jump too early or too late
- ☕ **Prioritize coffee** when energy drops below 25%
- ⚠️ Watch the **❗ NEED COFFEE ❗** warning — act fast!
- 🐛 Bugs come in clusters — stay alert at higher speeds
- 🏃 The first 15 seconds are your warm-up — use them wisely

---

## 👾 Game States

| State | Trigger |
|---|---|
| 🏃 Running | Game is active |
| 💀 Game Over | Energy = 0% |
| 🏆 Deploy Success | Survived 60 seconds |


---

*"Every bug you dodge is a production incident avoided."* 🐞
