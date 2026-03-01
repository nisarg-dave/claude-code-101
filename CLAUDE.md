# CLAUDE.md

This file provides guidance to Claude Code (claude.ai/code) when working with code in this repository.

## Project Overview

This is a simple Tic Tac Toe game collection with two implementations:
- **tictactoe.html**: Classic 2D grid-based Tic Tac Toe
- **tictactoe3d.html**: 3D version using Three.js with a rotatable 3x3x3 cube

No build steps, tests, or linting required. These are standalone HTML files that run directly in a browser.

## Running the Project

Open HTML files directly in a browser:
```bash
open tictactoe.html      # 2D version
open tictactoe3d.html    # 3D version
```

## Repository

GitHub: https://github.com/nisarg-dave/tictactoe

## Version Control

Commit and push to GitHub regularly with clean, descriptive commit messages after completing meaningful work. This ensures the project state is always backed up and nothing is lost.

## Key Details

- **3D version** (tictactoe3d.html) uses Three.js via CDN and implements 49 winning combinations across 3D space
- Both files share the same visual design (Outfit font, dark navy background, red X / blue O colors)
- The 3D version supports mouse drag rotation and auto-rotation
