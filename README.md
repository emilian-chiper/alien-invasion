# alien-invasion
A simple implementation of Alien Invasion using Pygame

### STEPS
1. [Project Setup](#project-setup)
2. [Start Game Project](#start-project)
3. [Add Ship Image](#add-ship-image)
4. [Refactor: `_check_events()` and `_update_screen()`](#refactor)
5. [Piloting the Ship](#pilot-ship)

#### Project Setup
1. Create virtual environment: `python3 -m venv .venv`
2. Initialize virtual environment: `source .venv/bin/activate`
3. Install Pygame library within the virtual environment (locally): `pip install pygame`
4. Configure LSP -- create `pyrightconfig.json`

#### Start Game Project
1. Create Pygame Window and setup listeners for keyboard and mouse events.
2. Add frame rate control logic.
3. Set background color.
4. Create and instantiate game settings module.

#### Add Ship Image
1. Create and instantiate ship module.
2. Draw ship to screen.

#### Refactor
1. Create `_check_events()` method to contain keyboard and mouse events.
2. Create `_update_screen()` method to contain screen refresh logic.

#### Piloting the Ship
1. Create keydown event listener for right arrow key to move ship to the right.
2. Enable continuous movement.
3. Add leftward ship movement logic.
4. Adjust ship speed.
5. Limit ship range up to game window edges.
6. Refactor `_check_events()` method into `_keydown` and `_keyup` private methods.
7. Add keydown event for `Q` in order to quit game.
