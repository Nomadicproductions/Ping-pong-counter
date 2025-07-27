# Ping Pong Hit Counter

A simple web application for counting ping pong paddle hits using your computer's microphone.

## Overview

This project allows you to count the number of times you hit a ping pong ball by detecting sound spikes via your device's microphone. The web interface displays the current hit count in real time and provides controls to start counting and reset the counter.

## Features

- **Real-time Hit Detection:** Uses audio input from your microphone to detect ping pong paddle hits.
- **Live Counter Display:** Shows the current hit count in a large, readable format.
- **Simple Controls:** Start/stop listening and reset the counter with intuitive buttons.
- **Visual Status Indicator:** See whether the app is actively listening or has access to your microphone.

## How It Works

The app leverages the Web Audio API:
- Requests access to your microphone when you click "Start Counting".
- Analyzes the audio stream for spikes in volume that indicate a ping pong hit.
- Increases the hit count and updates the display each time a hit is detected.
- Allows you to reset the count at any time.

## Usage

1. **Clone or Download the Repository**
   ```
   git clone https://github.com/Nomadicproductions/Ping-pong-counter.git
   ```

2. **Open `index.html` in your web browser**
   - No server or additional dependencies required.

3. **Grant Microphone Access**
   - When you click the "Start Counting" button, your browser will prompt you to allow microphone access.
   - Denying access will prevent the counter from working.

4. **Start Playing!**
   - Hit your ping pong ball with the paddle. Each hit should increment the counter.
   - Use the "Reset Counter" button to start over.

## Requirements

- Modern web browser (Chrome, Firefox, Edge, etc.)
- Microphone

## Customization

You can adjust the sensitivity and timing parameters in the JavaScript section of `index.html` for different environments or paddle/ball types.

## License

MIT License

---

*Made by Nomadicproductions*
