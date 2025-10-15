# 🧭 Radar Undead 💀

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](LICENSE)
![Language: JavaScript](https://img.shields.io/badge/Language-JavaScript-blue.svg)

**Radar Undead** is an interactive zombie radar game built with HTML, CSS, and JavaScript. Players defend themselves from zombies appearing via sensor input from an Arduino, tracking them on a radar and shooting them down before they reach the center danger zone. 

## Features

- **Dynamic Radar Display**: A semicircular radar shows approaching zombies with real-time angle and distance updates.  
- **Arduino Integration**: Zombies can spawn randomly based on objects detected by an Arduino sensor.  
- **Interactive Shooting**: Click on the radar to shoot zombies and earn points.  
- **Difficulty Levels**: Easy, Medium, and Hard modes affect zombie spawn rates and challenge.  
- **Health Management**: Zombies reaching the center zone reduce player health. Game ends when health reaches zero.  
- **Immersive Audio**: Custom gunshot, zombie hit, groans, victory, and game-over sounds using Web Audio API.  
- **Responsive Visual Effects**: Pulsing zombies, distance indicators, and center danger zone highlights.  

## Technologies Used

- **HTML5** – Game structure and canvas rendering  
- **CSS3** – Styling, animations, and feedback effects  
- **JavaScript (ES6+)** – Game logic, radar mechanics, zombie management, Arduino communication, audio handling  
- **Web Audio API** – Custom sound effects and music generation  
- **Web Serial API** – Arduino connection and sensor data input  

## How To Play

The project is currently **not hosted as a website, but will be soon**. To play, simply clone the repository open the `index.html` file in a modern browser (Chrome or Edge recommended for Web Serial support).

## License

This project is licensed under the **MIT License** – see the [LICENSE](LICENSE) file for details.  

---

### Made with ⚡️ by July Wu, please star if you find it fun!
