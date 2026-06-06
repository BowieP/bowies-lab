# 🌍 Bowie's 3D World

Bowie's 3D World is a lightweight, browser-based voxel sandbox game. Built entirely with HTML, JavaScript, and Three.js, it features procedurally generated infinite terrain, dynamic fluid mechanics, and interactive block-building capabilities, all running seamlessly in the client.

## ✨ Features

* **Procedural Generation:** Utilizes Simplex Noise to generate infinite, distinct biomes and terrain on the fly.
* **High Performance:** Leverages `THREE.InstancedMesh` to render tens of thousands of blocks smoothly at high frame rates.
* **Dynamic Fluid Mechanics:** Includes an algorithm for water blocks to spread and flow downwards and outwards.
* **Entity System:** Features a custom spawning system and basic AI for wandering entities (pigs, sheep, cows, and chickens).
* **Responsive UI:** The interface is built with Tailwind CSS, ensuring the toolbox and game controls are fully responsive across desktop and mobile devices.

## 🛠️ Technology Stack

* **Graphics:** [Three.js](https://threejs.org/) (WebGL)
* **Styling:** [Tailwind CSS](https://tailwindcss.com/)
* **World Generation:** [Simplex-Noise.js](https://github.com/jwagner/simplex-noise.js)
* **Core:** Vanilla JavaScript & HTML5 Canvas

## 🚀 Getting Started

1. **Open the game:**
   Navigate to the project directory and simply open `index.html` in any modern web browser. 

## 🎮 Controls

* **Desktop:** Click and drag the mouse to rotate the camera. Left-click to place or break blocks based on your selected tool.
* **Mobile/Tablet:** Swipe to pan the camera. Pinch to zoom. Tap to interact with the environment.
* **Tool Menu:** Access the floating toolbox in the top-left corner to switch between blocks, breaking tools, and entity spawners.

## 👋 Bye!

Thanks for visiting and checking out the project. Happy building!
