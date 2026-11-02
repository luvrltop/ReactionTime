# ReactionTime
A reaction time game for Flipper Zero, written in C. 

## Game idea:
Wait for the signal, then press OK as fast as you can.

## How to play
1. Press **OK** on the start screen.
2. Wait for **PRESS!!!** to appear. The delay until **PRESS!!!** is randomized (1.5-5 s).
3. Press **OK** as fast as you can. Your reaction time is shown in milliseconds.


## Controls
| Button | Action |
|---|---|
| OK | Start / react / play again |
| Left | Reset stats (in start screen(aka. menu)) |
| Back | Return to start screen / exit app |

## Stats
Your results are saved to `apps_data/reaction_time/stats.txt` on the SD card. The file stores the total of all your reaction times and the number of rounds played. From these, your average reaction time is calculated and shown on the start screen. The stats persist between sessions until you reset them.

## Installing
Drag and drop the reaction_time.fap file into the 'apps/Games/' folder on your Flipper Zero.

## Building it yourself
Requires [ufbt](https://github.com/flipperdevices/flipperzero-ufbt).

    ufbt launch

## License
MIT
