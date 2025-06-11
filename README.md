# Elokapina Game

This repository contains a small browser based game written in Python using [PyScript](https://pyscript.net/). The goal is to collect supporters by clicking the **Protest** button. When you reach 10 supporters you win.

## Running locally

1. Make sure you have a modern web browser (Chrome, Firefox or Edge).
2. Clone this repository or download the source.
3. Open `index.html` in your browser. No additional setup is required because the Python runtime is loaded from the PyScript CDN.

## Publishing on a website

You can host the game as a static web page. Here is a simple approach using GitHub Pages:

1. Push this repository to GitHub.
2. In the repository settings enable **GitHub Pages** and choose the `main` branch.
3. After a short delay your game will be available at `https://<your-username>.github.io/<repository-name>/`.

Any web host that can serve static files will also work. Just upload `index.html`.
