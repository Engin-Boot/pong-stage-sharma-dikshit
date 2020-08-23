# Select game mode

## Feature

Allows the user to create a new game, resume a saved instance of the game.

## Scenario : Staring a new game

- Given: Opened/Running game.
- When: User selects to create a new game.
- Then: Create a new profile of the game and provide options how the user widh
to start the game.

## Scenario : Loading a saved profile

- Given: Opened/Running game.
- When: User selects to load the saved profile.
- Then: Load the progress of the saved instance of the game.

## Scenario : Resuming a ongoing instance of the game.

- Given: Opened/Running game.
- When: User wants to continue to ongoing paused instance of the game.
- Then: Resume the game after a countdown of 3.
