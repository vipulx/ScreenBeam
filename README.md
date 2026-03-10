<h1 align="center">
  ScreenBeam 💡
</h1>

<p align="center">
  <strong>Turn your monitor into a professional, customizable virtual ring light.</strong>
</p>

<p align="center">
  <a href="https://vipulx.github.io/ScreenBeam/">
    <img src="https://img.shields.io/badge/Launch%20App-Try%20For%20Free-4facfe?style=for-the-badge&logoColor=white" alt="Try For Free">
  </a>
</p>

## Overview

ScreenBeam is an advanced web-based lighting tool designed for remote workers, content creators, and streamers. When you don't have a physical ring light or studio setup available, ScreenBeam converts your display into a flexible, powerful digital light board.

Simply open the app, arrange customizable light shapes on your screen around your webcam window, and achieve professional 3-point lighting effects instantly.

## Features

✨ **Professional Light Types**: Choose between standard diffused panels or true hollow ring shapes (`◎`) to create authentic catchlights in your eyes.
<br>🎨 **Full Customization**: Independently adjust the color, intensity, size, and shape (Circle, Square, Ring) of every light source.
<br>👁️ **Visibility Toggles**: Easily hide or show individual lights without losing your configuration, perfect for testing your setup.
<br>🎛️ **Quick Presets**: Set up an instant 3-point lighting setup (Key, Fill, Rim) with the click of a button.
<br>📱 **Installable PWA**: Install ScreenBeam directly to your desktop or device home screen. It works 100% offline like a native app.
<br>👻 **Immersive Mode**: The glassmorphic control UI and your cursor automatically vanish after 3 seconds of inactivity to maximize illumination.

## Quick Start

You don't need to install or download anything to get started. Just launch the live version hosted on GitHub Pages!

### 👉 [Try ScreenBeam For Free](https://vipulx.github.io/ScreenBeam/)

### Usage Tips
1. Drag the lights around your screen to find the most flattering angles.
2. If using a dual-monitor setup, drag a light to the monitor nearest your face.
3. Once your lights are placed, double-click to enter Full-Screen mode for maximum brightness.
4. Let go of your mouse during a video call—the control panel will disappear so your screen becomes a perfect, uninterrupted light panel. 

## Local Development Setup

If you want to clone this project and modify it yourself, the setup is incredibly simple. There are no node modules or build steps required.

1. Clone the repository:
   ```bash
   git clone https://github.com/vipulx/ScreenBeam.git
   ```
2. Because it includes a Service Worker for offline PWA functionality, you **must** serve it over a local web server (opening the file directly via `file:///` will block the background worker).
3. If you have Python installed, you can simply run:
   ```bash
   python -m http.server 8080
   ```
4. Navigate to `http://localhost:8080/index.html` in your browser.

## Tech Stack
* Vanilla HTML5 / CSS3 / JavaScript
* DOM manipulation and Box-Shadow physics for light generation
* Service Worker & Manifest JSON for PWA offline capabilities
* Glassmorphism & Modern Google Fonts (`Outfit`)

---
<p align="center">
  Made with ❤️ for better video calls.
</p>
