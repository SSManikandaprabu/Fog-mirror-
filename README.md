# Breath on Glass (Fog Mirror)

An interactive digital fogged mirror web application using camera and microphone audio to simulate condensation, wiping, and drawing.

## Features

- Real-time webcam video feed mirroring the user's view
- Audio-reactive breath detection using Web Audio API to fog up the screen when breathing into the mic
- Manual fogging mode via spacebar or on-screen hold button
- Interactive glass wiping and drawing using mouse cursor or touchscreen gestures
- Simulated shower condensation mode with natural downward water droplets and drips
- Adjustable brush size, ambient humidity level, and fog opacity sliders
- Snapshot capture tool to export drawings on fogged glass as PNG
- No-camera fallback mode for non-webcam devices
- **100% client-side privacy**: 100% client-side privacy: all audio and camera data stay entirely within the browser

## Tech Stack

- HTML5 Canvas API
- CSS3 / Backdrop Filter
- JavaScript (Vanilla ES6)
- WebRTC MediaDevices API (getUserMedia)
- Web Audio API (AudioContext & AnalyserNode)

## Screenshots

<!-- TODO: Add application screenshots here -->
![Breath on Glass (Fog Mirror) Screenshot](https://via.placeholder.com/800x450.png?text=Breath+on+Glass+(Fog+Mirror))

## Folder Structure

```
Fog-mirror-/
├── Breath on Glass (1).html
└── README.md
```

## Installation & Setup

This is a standalone, client-side web application. No complex build pipelines, database configurations, or package installations are required.

1. **Clone the repository:**
   ```bash
   git clone https://github.com/SSManikandaprabu/Fog-mirror-.git
   cd Fog-mirror-
   ```

2. **Run the application:**
   - **Direct Browser Launch**: Double-click `Breath on Glass (1).html` to open it directly in any modern web browser (Chrome, Firefox, Safari, Edge).
   - **Or via Local HTTP Server**:
     ```bash
     python -m http.server 8000
     ```
     Then open [http://localhost:8000/Breath on Glass (1).html](http://localhost:8000/Breath on Glass (1).html) in your browser.

## Usage

1. Launch the application in your browser following the setup instructions above.
2. Interact with the application controls and input fields tailored for Breath on Glass (Fog Mirror).
3. Preferences and data are stored locally in your browser's LocalStorage where applicable.

## Environment Variables

None required. Runs 100% locally in the browser with client-side camera/mic permissions.

## Live Demo Link

<!-- TODO: Add live demo link once deployed (e.g. GitHub Pages or Vercel) -->
_No live demo link currently configured. Refer to the TODO section below._

## Project Roadmap & TODOs

- [ ] Add real screenshot of the fogged mirror drawing effect
- [ ] Configure GitHub Pages deployment

## Author

- **S.S. Manikanda Prabu** - [GitHub Profile](https://github.com/SSManikandaprabu)
