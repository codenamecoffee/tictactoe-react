# 🕹️ Tic Tac Toe : React + Vite  

> 🎮 A simple implementation of the classic Tic Tac Toe game built with React and Vite.

> (ES) Una implementación simple del clásico juego Tic Tac Toe creado con React y Vite.

<br>

## 📌 Description / Descripción

**EN**  
This is a simple two-player Tic Tac Toe game created as part of my learning path in React. It's based on a freeCodeCamp tutorial, with some minor personal touches and style customizations. The game logic is basic and requires two people to play on the same device. The game interface and messages are in Spanish.

**ES**  
Este es un sencillo juego de tres en línea para dos personas, creado como parte de mi proceso de aprendizaje en React. Está basado en un tutorial de freeCodeCamp, al cual le realicé pequeños cambios personales y personalización de estilos. La lógica del juego es básica y requiere dos jugadores en el mismo dispositivo. La interfaz y los mensajes del juego están en español.

<br>

## 🎥 Demo 

![Demo del juego](./demo.gif)

<br>

- You can try this game live [here.](https://codenamecoffee.github.io/tictactoe-react/)
- Puedes probar el juego en vivo [aquí.](https://codenamecoffee.github.io/tictactoe-react/)
  
<br>

## ⚙️ How to Run / Cómo ejecutar

### With Yarn:

```bash
yarn
yarn run dev
```

### With NPM:

```bash
npm install
npm run dev
```

<br>

> Then open your browser and visit the local server URL provided in the terminal (usually `http://localhost:5173`).

> Luego abre el navegador y visita la URL del server local que muestra la terminal (normalmente `http://localhost:5173`) 

<br>

## 🌐 Deploying to GitHub Pages (with Yarn)

If you change the repository name or want to deploy your Vite + React project to GitHub Pages, follow these steps:

1. **Update the `base` property in `vite.config.js`:**
   ```js
   // vite.config.js
   export default {
     base: '/your-repo-name/',
     // ...other config...
   }
   ```
   Replace `your-repo-name` with your actual repository name.

2. **Install the gh-pages package:**
   ```bash
   yarn add --dev gh-pages
   ```

3. **Build your project:**
   ```bash
   yarn build
   ```

4. **Deploy the build folder to GitHub Pages:**
   ```bash
   yarn deploy
   ```

5. **Configure GitHub Pages:**
   - Go to your repository on GitHub.
   - Click on **Settings** > **Pages**.
   - Set the source to the `gh-pages` branch.

6. **Access your site:**
   - Your site will be available at:  
     `https://<your-username>.github.io/<your-repo-name>/`

**Note:**  
If you change your repository name, update all references to the old name in your project files and README.

<br>

## 🚀 Technologies Used / Tecnologías utilizadas

* React

* Vite

* JavaScript

* CSS

<br>

## 🧠 Potential Improvements / Posibles mejoras

* (EN) Add a toggle visual theme dark/light mode
* (ES) Agregar un tema visual que pueda alternar entre claro/oscuro

<br>

* (EN) Allow to restart the game without refreshing
* (ES) Permitir el reinicio del juego sin refrescar

<br>

* (EN) Implement a single-player mode with AI
* (ES) Implementar un modo de un jugador usando IA

<br>

* (EN) Track wins/losses and draw statistics
* (ES) Emplear seguimiento de partidas ganadas/perdidas y mostrar estadísticas

<br>
    
## 📚 Credits / Créditos

* (EN) Based on a freeCodeCamp tutorial on YouTube, with personal modifications and styling.

* (ES) Basado en un tutorial de freeCodeCamp en Youtube, con modificaciones personales y estilo.

<br>

> Created by Federico González - 2024
