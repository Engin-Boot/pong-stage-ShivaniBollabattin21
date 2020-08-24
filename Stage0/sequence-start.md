# Interaction Sequences

## Start up Sequence

The sequence is as follows:
trigger-input-->collision-checker-->calculate-score-->
declare-winner-->quit-game  

## Movement Initiation

Initially when players start the game the ball triggers from
left to right, when ball coincides with the player's wall,
the game checks -
         1. if ball has hit the 1st player's wall, a point adds up
           to 2nd player's scoreboard.
        2. else if it has hit 2nd player's wall, a point adds up
           to 1st player scoreboard.

if score of one of the player reaches 10, that player is winner.
After declaration of winner, the game asks player whether he/she
wants to quit, if yes the game terminates, else the game starts
again.

## One score

After collision-checker module finds a collision
it calls the calculate-score module to calculate
score of respective player.
