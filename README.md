# Dev Room Wallpaper

An interactive 3D isometric developer room you can use as a live wallpaper. It's a single `index.html` built with [Three.js](https://threejs.org/), and there's no build step.

https://github.com/user-attachments/assets/b4fac8a3-2bc2-4cb7-9bea-78957291a4bc

## Features

- **3D isometric room**: drag to rotate, scroll to zoom, double-click to fly in
- **Camera spots and tour**: jump to preset viewpoints or let the camera tour the room on its own
- **Space / City view**: switch the scenery outside the window
- **Background music**: calm ambient music generated live in the browser (no audio files). Press the ♪ Music button or `M` to play.
- **PIN-locked goals**: keep goals with step checklists and progress meters behind a 4–8 digit PIN, with a focus card that shows your current step
- **Local only**: everything is stored in your browser's `localStorage`, and nothing is sent to a server

## Usage

This is meant to run as a live desktop wallpaper:

1. Download or clone this repo.
2. Open a live-wallpaper app that can show web pages, such as [Plash](https://sindresorhus.com/plash) on macOS or [Lively Wallpaper](https://www.rocksdanister.com/lively/) on Windows.
3. Add `index.html` as the wallpaper.

You can also just open `index.html` in a browser to try it.

Browsers don't play sound until you interact with the page, so music starts only after you click ♪ Music or press `M`. To click it on your desktop, turn on your wallpaper app's interactive mode (in Plash this is called Browsing Mode).

## Controls

| Input | Action |
| --- | --- |
| Drag | Rotate |
| Scroll | Zoom |
| Double-click | Fly in |
| `1`–`5` | Fly to preset spots |
| `F` | Start or stop the tour |
| `0` | Reset the camera |
| `V` | Switch between space and city view |
| `M` | Turn music on or off |
| `G` | Open goals |
| `L` | Lock goals |
| `Esc` | Close the goals panel |

## Tech

- Three.js r128 (loaded from cdnjs)
- JetBrains Mono (Google Fonts)
- Plain HTML, CSS, and JavaScript
