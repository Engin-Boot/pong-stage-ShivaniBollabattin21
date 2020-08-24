# Check collisions

## Feature

What part of the game does this module deliver? To check collisions of the ball
and pass to the score module.

## Acceptance Criteria

### Scenario: Ball coincides with the wall

  Given: The game has begin.

  When: Ball coincides with the either sides of the wall.

  Then: The module checks if it has hit the player's wall,
        if yes it passes the flag to calculate-score module.  
