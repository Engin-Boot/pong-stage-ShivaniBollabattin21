# Quit Game

## Feature

What part of the game does this module deliver? Terminates the game.

## Acceptance Criteria

### Scenario: After declaration of winner and players want to quit
  
  Given: The game declares winner.
  
  When: First or second player clicks on quit button .

  Then: The game asks whether to quit or to continue,
        if player clicks on quit, the game ends
        else if player clicks continue, the game starts again.
  