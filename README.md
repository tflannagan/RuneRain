# Rune Rain

Rune Rain is a mesmerizing visual animation that creates a "digital rain" effect using ancient Norse runes. This project generates a dynamic, Matrix-like cascade of glowing runes against a dark background, creating an atmospheric and intriguing visual display.

## Live Demo

[Rune Rain Live Demo](https://tflannagan.github.io/RuneRain/)

## Features

* Full-screen canvas animation
* Falling runes with random selection from the Elder Futhark alphabet
* Dynamic color scheme with glowing effects
* Responsive design that adapts to window resizing
* Smooth animation with optimized performance

## How It Works

1. The script creates a canvas that fills the entire browser window.
2. It generates columns of falling runes, each rune randomly selected from the Elder Futhark alphabet.
3. Some runes randomly start glowing with either a primary (cyan) or secondary (pink) color.
4. The animation creates a fading effect, giving the illusion of runes disappearing as they fall.
5. When a column reaches the bottom of the screen, it has a chance to reset to the top.

## Technical Details

* Built with vanilla JavaScript and HTML5 Canvas
* No external dependencies required
* Utilizes `requestAnimationFrame` for smooth animation
* Implements a custom color scheme for visual appeal
