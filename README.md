# String Pull

Invisible strings connect your fingertips to objects on screen. Move your fingers and objects follow like a puppeteer. Fist to pull everything together. Open palm to explode. Flick to fling.

![Demo](https://img.shields.io/badge/status-live-brightgreen) ![Tech](https://img.shields.io/badge/tech-MediaPipe%20%2B%20Matter.js%20%2B%20Canvas-blue)

## How to Use

1. Open `index.html` in Chrome/Edge
2. Allow camera access
3. Raise your hand — strings connect to objects
4. **Move fingers** — objects follow each fingertip
5. **Make a fist** — all objects pull to your palm
6. **Open palm wide** — objects explode outward
7. **Flick a finger** — fling that object with velocity
8. **Tab key** — switch object sets
9. **R key** — reset objects

## Features

- **5 string connections** — each fingertip controls an object
- **Catenary string curves** — drooping when slack, taut when pulled
- **String vibration** — visible vibration on taut strings
- **Real physics** — gravity, collision, bounce, friction (Matter.js)
- **Fist gesture** — magnetic pull to palm center
- **Open palm** — explosive force pushes everything away
- **Flick detection** — fast finger movement flings objects
- **Object trails** — motion blur behind fast objects
- **Collision sounds** — percussive thud proportional to impact
- **4 object sets** — balls, emojis, letters, planets
- **Video recording** — REC button captures with audio
- **Screenshot** — SNAP button saves PNG
- **EMA landmark smoothing** — jitter-free tracking

## Object Sets

| Set | What |
|-----|------|
| Balls | Colored spheres with gradient shading |
| Emoji | Fun emoji characters |
| Letters | Spells "STRINGPULL" with colored letters |
| Planets | Different sized planetary bodies |

## Tech Stack

- **@mediapipe/tasks-vision** — hand landmark detection (GPU)
- **Matter.js** — 2D physics engine (gravity, collisions, springs)
- **Canvas 2D** — rendering with compositing and gradients
- **Web Audio API** — procedural collision/gesture sounds
- **Single HTML file** — no build tools, no npm

## License

MIT
