# 15 Puzzle Game

Live demo: https://slidepuzzel15.netlify.app/  
Repository: https://github.com/Amanshaw445/15-puzzle-game

A simple, responsive implementation of the classic 15-puzzle (sliding puzzle) built with plain HTML, CSS and JavaScript.

## Table of contents
- [About](#about)
- [Demo](#demo)
- [How to play](#how-to-play)
- [Features](#features)
- [Run locally](#run-locally)
- [Project structure](#project-structure)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)
- [Author](#author)

## About
The 15 Puzzle is a sliding puzzle consisting of a 4x4 grid with 15 numbered tiles and one empty space. The goal is to arrange the tiles in numerical order by sliding tiles into the empty spot. This repository contains a lightweight web version suitable for desktop and mobile browsers.

## Demo
Try the live version here: https://slidepuzzel15.netlify.app/

## How to play
- Click or tap a tile adjacent to the empty space to slide it.
- Continue sliding tiles until the numbers are in order (1 → 15) with the empty space in the bottom-right corner.
- There may be a shuffle or reset button (see the UI) to start a new random solvable puzzle.

## Features
- Clean, minimal UI
- Click/tap controls suitable for desktop and mobile
- Shuffling that produces solvable configurations
- Move counter (if implemented in the UI)
- Responsive layout

## Run locally
To try the project locally:

1. Clone the repository
   git clone https://github.com/Amanshaw445/15-puzzle-game.git

2. Open the project folder and launch the app:
   - Option A: Open `index.html` directly in your browser.
   - Option B: Serve it with a static server (recommended for some browser features):
     - Using Python 3: `python -m http.server` (then open http://localhost:8000)
     - Using VS Code Live Server extension or any static file server

No build step or package manager is required — the app runs using plain HTML/CSS/JS.

## Project structure
- index.html — main HTML file
- style.css — styles for the game
- script.js — game logic and interactivity
- README.md — project information (this file)

## Technologies
- HTML
- CSS
- JavaScript

(The repository language breakdown: JavaScript, CSS, HTML.)

## Contributing
Contributions, suggestions and improvements are welcome.

- If you find a bug or want a feature, please open an issue.
- For code changes: fork the repo, create a branch, make your changes and open a pull request.

Please keep changes focused and include a short description of what you changed and why.

## License
No license is specified in this repository. If you'd like others to use or contribute under a specific license, add a LICENSE file (for example, MIT) to the repository.

## Author
Aman Shaw — https://github.com/Amanshaw445

Credits: inspired by the classic 15-puzzle game.
