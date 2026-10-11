# Dev Room Wallpaper

An interactive 3D isometric developer room you can use as a live wallpaper. It's a single `index.html` built with [Three.js](https://threejs.org/), and there's no build step.

https://github.com/user-attachments/assets/b4fac8a3-2bc2-4cb7-9bea-78957291a4bc

## Features

- **3D isometric room**: drag to rotate, scroll to zoom, double-click to fly in
- **Camera spots and tour**: jump to preset viewpoints or let the camera tour the room on its own
- **Space / City view**: switch the scenery outside the window
- **PIN-locked goals**: keep goals with step checklists and progress meters behind a 4–8 digit PIN, with a focus card that shows your current step
- **Local only**: everything is stored in your browser's `localStorage`, and nothing is sent to a server

## Usage

Open `index.html` in a browser. You can also serve it locally:

```sh
python3 -m http.server 8000
# then visit http://localhost:8000
```

To use it as a desktop wallpaper, point a live-wallpaper app that supports web pages at the file or URL. Examples are [Plash](https://sindresorhus.com/plash) on macOS and [Lively Wallpaper](https://www.rocksdanister.com/lively/) on Windows.

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
| `G` | Open goals |
| `L` | Lock goals |
| `Esc` | Close the goals panel |

## Tech

- Three.js r128 (loaded from cdnjs)
- JetBrains Mono (Google Fonts)
- Plain HTML, CSS, and JavaScript
