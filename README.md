# 🧑‍💻 Semana do Zero ao Programador Contratado – Character Showcase

This project is an interactive character gallery developed during the **"Semana do Zero ao Programrador Contratado"** event, with a visual theme inspired by futuristic programmers and digital heroes (with a subtle nod to Dragon Ball’s energetic style).

Users can browse through 5 unique characters (`Cyberstorm`, `CodePixie`, `HexBlade`, `NeonPulse`, `Codebreaker`) by clicking on their respective icons. Each character has a full‑screen background image, a name, and a descriptive text that changes dynamically.

---

## 🚀 Technologies Used

- **HTML5** – page structure and semantic markup  
- **CSS3** – styling, responsive layout, and animations (`estilos.css`, `reset.css`, `responsivo.css`)  
- **JavaScript** – interactivity (character switching logic)  
- **Google Fonts** – *Rubik* and *Secular One* typography  

---

## 📁 Project Structure
project-root/
│
├── index.html
├── src/
│ ├── css/
│ │ ├── reset.css
│ │ ├── estilos.css
│ │ └── responsivo.css
│ ├── imagens/
│ │ ├── bg-cyberstorm.png
│ │ ├── bg-cyberstorm-mobile.png
│ │ ├── icone-cyberstorm.png
│ │ ├── (other background and icon files)
│ │ └── ...
│ └── js/
│ └── index.js
└── README.md


---

## ✨ Features

- **Dynamic character switching** – Click a button at the bottom to change the displayed character.  
- **Responsive design** – Different background images for desktop (`.png`) and mobile (`-mobile.png`) via `<picture>` and `media` queries.  
- **Visual feedback** – The active button receives a `.selecionado` class for styling.  
- **Smooth content transition** – Character name and description update instantly.

---

## 🖥️ How to Run Locally

1. **Clone the repository**  
   ```bash
   git clone https://github.com/regbf/Website_DragonBall_Project.git
