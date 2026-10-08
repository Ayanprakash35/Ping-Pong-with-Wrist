# Wrist-Controlled Ping Pong

A game of ping pong against the computer where your paddle is your right wrist. The webcam tracks your arm with PoseNet and the paddle follows it up and down.

**[Live demo →](https://ayanprakash35.github.io/Ping-Pong-with-Wrist/)**

## Features

- Paddle controlled by right-wrist tracking via **PoseNet**
- Computer opponent, scoring and sound effects
- Ball speeds up with every return

## How to play

1. Stand 3–4 feet back from your laptop so your upper body is in frame.
2. Raise your right wrist until a red dot appears on the left edge.
3. Press **Start ping ponging** and move your wrist up and down to return the ball.
4. The computer wins at 4 points. Press **Restart** for another go.

## Built with

[p5.js](https://p5js.org/) + p5.sound, [ml5.js](https://ml5js.org/) PoseNet

## Run it locally

The webcam needs a page served over `http://localhost` (not opened as a file):

```bash
git clone https://github.com/Ayanprakash35/Ping-Pong-with-Wrist.git
cd Ping-Pong-with-Wrist
python3 -m http.server 8000
```

Then open <http://localhost:8000> and allow camera access.

Everything runs in the browser. No video leaves your machine.
