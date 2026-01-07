# 🌌 Solar & Lunar Eclipse Simulation

A high-performance, interactive 2D Canvas simulation that visualizes the celestial mechanics of Earth, the Moon, and the Sun. This project demonstrates the alignment of celestial bodies during solar and lunar eclipses using pseudo-3D perspective rendering.

![Eclipse Simulation Banner](https://via.placeholder.com/800x300/0d1117/ffffff?text=Solar+%26+Lunar+Eclipse+Simulation)  
*Replace with actual screenshot or Shutterstock attribution if needed*

---

##  Features

- **Real-time Simulation**: Smooth 60 FPS animation using `requestAnimationFrame`.
- **Three Modes of Operation**:
  - **Normal Orbit**: Standard movement of the Moon around Earth and Earth around the Sun.
  - **Solar Eclipse**: Visualizes the Moon passing between the Earth and the Sun.
  - **Lunar Eclipse**: Visualizes the Earth passing between the Sun and the Moon.
- **Interactive UI**: Elegant control panel with real-time descriptions.
- **Shadow Physics**: Dynamic shadow casting logic based on the light source (The Sun).
- **Pseudo-3D Rendering**: Uses mathematical scaling and depth (Z-axis) to create a 3D feel on a 2D canvas.
- **Performance Monitor**: Live tracking of FPS and orbital angles.

---

##  How to Use

### Control via UI
Simply click the buttons in the top control panel to switch between:
- **Normal Orbit** 🌍
- **Solar Eclipse** 🌑
- **Lunar Eclipse** 🌕

### Keyboard Shortcuts
| Key | Action |
|-----|--------|
| `N` | Switch to **Normal Orbit** |
| `E` | Switch to **Solar Eclipse** |
| `L` | Switch to **Lunar Eclipse** |
| `ESC` | Stop the Simulation |

---

##  Technology Stack

- **HTML5**: Structure and Canvas element.
- **CSS3**: Glassmorphism UI, radial gradients, and animations.
- **JavaScript (Vanilla)**: Trigonometric math for orbits, rendering logic, and event handling.

---

