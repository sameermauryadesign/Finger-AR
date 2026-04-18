# Finger-AR
**🌌 Nature Aura AR - Advanced Finger Tracking Experience**

**Nature Aura AR** is an interactive, browser-based augmented reality experience powered by real-time hand tracking. Using **MediaPipe Hands**, it transforms your hand movements into stunning neon visual effects, particles, and audio feedback - all running directly in the browser.

**🚀 Features**

**✋ Real-Time Hand Tracking**

- Detects up to **2 hands simultaneously**
- Tracks **21 landmarks per hand**
- Uses **MediaPipe Hands** for accurate tracking

**🎨 Visual Effects Engine**

- Neon glowing hand skeletons
- Particle trails from fingertips
- Shockwaves on pinch gestures
- Dynamic lightning connections between hands
- Rotating mandala effects for multi-hand interactions

**🌈 Multiple Themes**

Switch between immersive visual styles:

- Rainbow
- Cyberpunk
- Lava
- Ocean
- Galaxy

**🎵 Audio Interaction**

- Dynamic background hum based on hand distance
- Sound effects triggered by gestures (e.g., pinch = zap)

**🧠 Gesture Detection**

- **Pinch Gesture** → Creates shockwave + sound
- **Hand Spread Detection** → Measures openness
- Gesture feedback displayed in UI

**📊 HUD (Heads-Up Display)**

- Hands detected
- FPS counter
- Current gesture
- Hand spread percentage

**🌌 Animated Background**

- Matrix-style digital rain
- Speed reacts to hand motion velocity

**🛠️ Tech Stack**

- **HTML5 / CSS3 / JavaScript**
- **Canvas API** (2D rendering)
- **Web Audio API**
- **MediaPipe Hands (CDN)**

**📦 Installation & Usage**

**1\. Clone or Download**

git clone &lt;your-repo-url&gt;

cd neon-aura-ar

**2\. Run the Project**

Simply open the file:

index.html

Or use a local server (recommended):

npx serve .

**3\. Grant Permissions**

- Allow **camera access**
- Click **"Enter Experience"**

**🎮 How to Use**

| **Action**        | **Effect**                        |
| ----------------- | --------------------------------- |
| Move hands        | Creates particle trails           |
| Pinch fingers     | Triggers shockwave + sound        |
| Use both hands    | Generates lightning + connections |
| Move hands faster | Speeds up background animation    |
| Switch theme      | Changes visual style              |

**📁 Project Structure**

.

├── index.html # Main application (UI + logic + rendering)

**⚙️ Configuration Highlights**

- **Themes** are dynamically generated using HSL colors
- **Physics engine** handles particles and ripples
- **Canvas layering**:
  - bgCanvas → background effects
  - mainCanvas → interactions and visuals
- **Audio engine** uses oscillators for real-time synthesis

**⚠️ Requirements**

- Modern browser (Chrome recommended)
- Webcam support
- Internet connection (for MediaPipe CDN)

**🔮 Future Improvements**

- Mobile optimization
- More gesture controls
- Multiplayer interaction
- AR object manipulation
- Custom theme creator

**📸 Preview**

A futuristic neon AR interface where your hands control light, energy, and sound.

**🧑‍💻 Author**

**Sameer Maurya**
