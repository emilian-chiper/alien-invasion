# alien-invasion
A simple implementation of Alien Invasion using Pygame

### STEPS
1. [Project Setup](#project-setup)
2. [Start Game Project](#start-project)
3. [Add Ship Image](#add-ship-image)
4. [Refactor: `_check_events()` and `_update_screen()`](#refactor)

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
