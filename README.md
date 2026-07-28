# Air Canvas Pro vN/A - Browser Hand-Tracking Drawing App 2026

> **Air Canvas Pro is a web-based drawing tool that converts camera-tracked hand movements and gestures into artwork on an HTML5 canvas.**

[![Platform](https://img.shields.io/badge/Platform-web%20browser-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-N%2FA-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliverlewispnhh1466/air-canvas-pro-hand-draw?style=flat-square)](https://github.com/oliverlewispnhh1466/air-canvas-pro-hand-draw)

---

<p align="center">
  <a href="https://oliverlewispnhh1466.github.io/air-canvas-pro-hand-draw/">
    <img src="https://img.shields.io/badge/Download-Air%20Canvas%20Pro%20Latest-brightgreen?style=for-the-badge" alt="Download Air Canvas Pro">
  </a>
</p>

> **[Download Air Canvas Pro](https://oliverlewispnhh1466.github.io/air-canvas-pro-hand-draw/)**

---

[Download Latest Build](https://oliverlewispnhh1466.github.io/air-canvas-pro-hand-draw/)

---

## Overview

Air Canvas Pro allows you to draw in a browser using your hand as the input device. The camera tracks your hand, while index-finger movement controls the canvas cursor and gestures provide actions that would normally require a mouse or touchscreen.

The application brings together MediaPipe hand tracking, an HTML5 Canvas workspace, and JavaScript-based controls. Users can choose colors, change brush size and opacity, and work with standard canvas actions. It is suitable for artists, classroom activities, presentations, and other touch-free creative use cases.

---

## Highlights

- Track a hand in real time through the browser camera
- Use index-finger movement to create strokes
- Temporarily stop drawing with a two-finger gesture
- Switch to erasing by displaying an open palm
- Pick colors from the integrated color selector
- Change brush dimensions and transparency during a session
- Undo the latest canvas operations or remove all canvas content
- Expand the workspace with optional fullscreen mode
- Display the hand skeleton to make gesture tracking easier to follow
- Use cursor interpolation for smoother pointer movement

---

## Getting Started

### Use the hosted browser build

1. Visit [Download Latest Build](https://oliverlewispnhh1466.github.io/air-canvas-pro-hand-draw/).
2. Open the application in a supported modern browser.
3. Accept the camera permission request.
4. Keep your hand inside the camera view and move your index finger to draw.

### Clone and run the project locally

```bash
git clone https://github.com/oliverlewispnhh1466/air-canvas-pro-hand-draw.git
cd REPO
```

Open the primary HTML file in your browser. If camera access requires the page to be served from a web origin, use a local server instead.

For example:

```bash
python -m http.server 8000
```

Open the local address below after starting the server:

```text
http://localhost:8000
```

---

## Using the App

1. Launch Air Canvas Pro and approve camera access.
2. Place your hand where it remains visible to the camera.
3. Move your index finger to operate the drawing cursor.
4. Make a two-finger gesture to pause or continue drawing.
5. Display an open palm to enter erase mode.
6. Choose a color and set the desired brush size and opacity.
7. Press Undo to reverse the most recent action.
8. Use Clear Canvas to remove the current composition.
9. Turn on fullscreen mode when you need a larger work area.
10. Show or hide the hand skeleton according to whether visual gesture feedback is helpful.

---

## In-App Settings

There is no separate configuration file. Air Canvas Pro exposes its drawing options directly in the browser interface, where they can be changed during use:

```text
Color:        Selected with the color picker
Brush size:   Controlled with the size setting
Opacity:      Controlled with the opacity setting
Gestures:     Index finger, two fingers, and open palm
Display:      Canvas, fullscreen, and hand skeleton options
```

The browser controls camera permission. If permission was rejected earlier, open the browser's site settings, allow camera access for the page, and reload Air Canvas Pro.

---

## System Requirements

- A current web browser with JavaScript enabled
- A functioning camera
- Browser permission to use that camera
- Hardware capable of running MediaPipe hand tracking
- Network access for the hosted application or any required browser resources
- Enough display area for the canvas and its controls

---

## Frequently Asked Questions

### Can I use Air Canvas Pro without a drawing tablet?

Yes. Drawing input comes from camera-based hand gestures, so a tablet or mouse is not required for the intended workflow.

### What are the steps to begin drawing?

Open the application, grant camera access, and place your hand within the camera frame. Move your index finger across the canvas to control the cursor and draw.

### How do I pause drawing while keeping tracking enabled?

Make the two-finger gesture. Drawing will pause, but the hand-tracking session remains active.

### What gesture erases content?

Show an open palm, then move over the section of the canvas you want to erase.

### Are brush color and behavior adjustable?

Yes. The color picker, brush size setting, and opacity setting let you modify the brush while working.

### What can I do if hand tracking is inconsistent?

First verify that the camera is working, camera permission is enabled, and your hand is clearly visible within the frame. Improved lighting and an unobstructed view of the hand can also help the tracking feedback.

### How do I find the newest version?

Open the [latest build](https://oliverlewispnhh1466.github.io/air-canvas-pro-hand-draw/) for the current hosted application. Project updates are also available in the repository.

### Does the app support fullscreen drawing?

Yes. Fullscreen mode provides a larger area for creating artwork.

---

## License

Air Canvas Pro is released under the GNU GPL v3.0. See [LICENSE](LICENSE) for the full license details.
