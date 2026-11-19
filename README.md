# Marimo Desk Club

Marimo Desk Club is an interactive virtual desk for a short focus session or a quiet break. Tend to the marimo moss balls, switch on the desk lamp, and try a few pretend office tasks surrounded by original Strong Bailey artwork.

## Explore the desk

- Drag or rotate the marimo, make and pop bubbles, and pull the cord to toggle the lamp.
- Start a 25-minute focus timer and watch the leaf-shaped fairy lights glow while it runs.
- Browse a sample slide deck, write in a Word-style editor, or organize and compose messages in a fictional Gmail-style inbox.
- Open snack notes from the apple and fortune cookie.
- Select **Surprise me** for a night scene lit by the laptop screen. Select it again to return to daytime.

The note editor and demo inbox save changes in the browser using `localStorage`. The inbox is a simulation and cannot send real email.

## Built with

- **HTML** structures the desk and laptop apps in `index.html`.
- **CSS** styles and animates the scene and its controls.
- **Vanilla JavaScript** handles the timer, drag interactions, app state, and the night-mode toggle.
- **`assets/`** contains the Strong Bailey poster illustrations.

The site runs entirely in the browser and requires no build step or backend.

## Run locally

Open `index.html` in a browser, or start a local server from the project folder:

```sh
python -m http.server 8000
```

Then visit <http://localhost:8000>.

## License

The website code is licensed under the MIT License (see [LICENSE](LICENSE)).

Strong Bailey character, logo, and original artwork © 2026 Janice Mook. All rights reserved. These assets are not covered by the MIT License.
