# Declare winner

## Feature

What part of the game does this module deliver? checks score of the players
and declares winner accordingly.

## Acceptance Criteria

### Scenario: Score of either of the players reaches 10 (limit can change)

  Given: The game is going on.
  
  When: Total score of first player or second player reaches 10 .

  Then: declare-winner module declares first player as winner,
        if the score of first player is 10 else checks the score of
        second player, if it's 10 then declares second player
        as winner.
  