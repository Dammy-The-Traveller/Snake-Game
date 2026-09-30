# Snake Game

A simple browser-based Snake game built with HTML, CSS, and JavaScript.

## Features

- Classic Snake gameplay
- Score tracking
- Best score saved in browser local storage
- Restart and pause controls
- Difficulty levels: Easy, Medium, Hard
- Mobile-friendly touch controls and swipe support
- Responsive layout for desktop and Android browsers

## Demo

Open the project in a browser and play locally.

## Project Structure

```text
Snake-Game-main/
├── index.html
├── style.css
├── script.js
└── README.md
```

## How to Run

### Option 1: Local web server (recommended)

From the project folder, run:

```bash
python3 -m http.server 8000
```

Then open:

```text
http://localhost:8000
```

### Option 2: Open directly in a browser

You can also open `index.html` directly in a browser, but a local web server is recommended for better browser behavior and cache handling.

## Controls

### Desktop

- Arrow keys: move the snake
- Restart button: start a new game
- Pause button: pause or resume the game

### Mobile / Touch

- Swipe on the game area to move the snake
- Tap the on-screen arrow buttons to change direction

## Difficulty Levels

- Easy: slower snake speed
- Medium: balanced speed
- Hard: faster snake speed

## Gameplay

- Eat the glowing food to grow the snake
- Avoid hitting the walls
- Avoid colliding with your own body
- Try to beat your high score

## Technologies Used

- HTML5
- CSS3
- JavaScript

## License

This project is open for personal and educational use.

## Author

Built as a lightweight browser game project for learning JavaScript and game logic.
