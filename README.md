# 🧟 Zombies Shooter [PC Beta 1.0]

**Zombies Shooter** is a lightweight First-Person Shooter (FPS) game built entirely using **Vanilla JavaScript**, **HTML5 Canvas**, and **CSS3**. This project utilizes a classic **Raycasting Engine** (Pseudo-3D) to create a three-dimensional environment without the need for external game engines or libraries.

---

## 🚀 Key Features (Beta)
* **Custom Raycasting Engine:** High-performance 3D rendering logic (inspired by Wolfenstein 3D).
* **PC Optimized Controls:** Native support for Mouse Look and Keyboard input.
* **Dynamic Enemy AI:** Zombies that track and pursue the player's position in real-time.
* **Health & Combat System:** Integrated health bar and visual damage indicators (screen flash).
* **Minimalist UI:** Clean interface displaying score, health, and gameplay instructions.

---

## 🎮 How to Play

For the best experience, please use the **Google Chrome** browser on a Desktop/Laptop.

### Controls:
| Key | Action |
| :--- | :--- |
| **W / S** | Move Forward / Backward |
| **A / D** | Strafe Left / Right |
| **Mouse** | Rotate View (360° Horizontal) |
| **Left Click** | Shoot Zombies |

> **Pro Tip:** Click anywhere on the game screen to enable **Pointer Lock** (locks your cursor for FPS movement). Press `Esc` to release the mouse.

---

## 🛠️ Installation & Setup

### Running via Termux (Android):
If you are developing or testing this on mobile via Termux, you can host a local server:

1. Install Python: `pkg install python`
2. Navigate to the project folder: `cd ZombiesShooter`
3. Start the server: `python -m http.server 8001`
4. Open Chrome and visit: `localhost:8001`

### Running on PC:
Simply open the `zombies_shooter_pc.html` file directly in your web browser.

---

## 🧪 Project Status
This project is currently in the **Public Beta Testing** phase. Feedback is highly appreciated as I continue to develop:
- [ ] Ammo System & Reload Mechanics.
- [ ] Multiple Levels & Map Variety.
- [ ] Sound Effects (SFX) and Background Music.