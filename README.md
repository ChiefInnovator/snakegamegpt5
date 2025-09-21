# Neon Snake — GPT-5 Edition

A single-page, neon-styled take on Snake rendered with HTML5 Canvas and zero dependencies. Everything lives in `neon_snake_gpt5.html`, so you can run the game instantly in any modern desktop or mobile browser.

## Features
- Responsive grid that adapts automatically to your window or device size.
- Wrap/Walls mode toggle to choose between classic wrapping play or solid borders.
- Local best score tracking stored in `localStorage`, plus a quick reset button.
- Dynamic speed ramp as you eat apples, with the current multiplier shown on the HUD.
- Optional synth-like sound effects and haptics (for supported touch devices).
- Touch-friendly controls with swipe support alongside keyboard input.

## Controls
- `Arrow Keys` / `WASD` — steer the snake.
- `Space` — start, pause/resume, or restart from the overlay.
- `R` — reset the board.
- Click/tap the HUD pills to toggle Wrap/Walls mode, toggle sound, or reset best score.

## Run Locally
1. Clone or download this repository.
2. Open `neon_snake_gpt5.html` in your browser (double-clicking the file works on most systems).
3. Play immediately—no build step or server required.

## Customizing
Since the game is a single HTML file, you can tweak visuals, gameplay constants, or audio cues directly in `neon_snake_gpt5.html`. Some easy entry points:
- Adjust grid sizing in the `computeGrid` function.
- Modify growth and speed behavior near the `tick` function.
- Update colors in the `:root` CSS variables for a new palette.

Have fun chasing high scores under neon lights!
