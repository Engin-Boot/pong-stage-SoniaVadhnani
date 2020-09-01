# Movement of Ball and Racket

## Feature

This module is responsible for the speed and direction
in which the ball moves.

## Acceptance Criteria


### Scenario: Initially the Movement of ball is random

Given the game works efficiently and there is no error in
the game that may interrupt any functionality.

When the game starts as user hits START
and the ball is in center of the dashed white line.

Then the ball starts moving randomly in
any direction with a particular speed.

### Scenario: Ball changes direction when hits anything

Given the game works efficiently and there is no error
in the game that may interrupt any functionality,
and the ball is moving randomly.

When the ball hits the wall or the racket

Then the ball reflects back in other direction
with same angle that it strikes with.
