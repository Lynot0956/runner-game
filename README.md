# runner-game

**Offline Runner**: an endless runner where your character jumps over cacti and ducks under birds. The whole game is one file, `index.html`, and it has no dependencies. It needs no internet connection, no build step and no install.

## Play

Open `index.html` in any modern browser (double-click it). That's it.

| Action | Keyboard | Touch / mouse |
| --- | --- | --- |
| Jump (hold for a higher jump) | `Space`, `↑` or `W` | Tap the right side |
| Duck / fast-fall | `↓` or `S` | Hold the left side |
| Pause | `P` or `Esc` | Tap to resume |
| Sound on/off | `M` | |

## Features

- The game speeds up the longer you survive, and gaps between obstacles scale with speed so every obstacle can be cleared
- Cactus clusters of different sizes. Birds appear after 250 points and fly at three heights (jump, duck, or keep running)
- Variable jump height, coyote time and jump buffering so the controls feel responsive
- A day/night cycle every 700 points and parallax hills and clouds
- Sound effects made with the Web Audio API (no audio files)
- High score saved in your browser
- The game pauses automatically when you switch tabs
