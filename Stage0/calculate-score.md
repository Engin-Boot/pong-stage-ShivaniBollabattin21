# Calculate Score

## Feature

What part of the game does this module deliver? calculates score of the player.

## Acceptance Criteria

### Scenario: Calculate score for player

  Given: The game is going on.
  
  When: collision-checker module calls the calculate-score module.

  Then: Calculate-score module checks if the ball has hit first player's wall,
        if yes then - add point to second player,
        if no then - add point to first player.
  