# Movement of Ball and Racket

## Feature

This module is responsible for the speed and direction
in which the ball moves and also control the left and right
movement of rackets.

## Acceptance Criteria

### Scenario: Move user's racket according to user's input

Given two buttons left and right under user's racket
which works efficiently and it takes 6 left taps
to reach completely to the left from complete right and
vice versa.

When user taps on any of the button

Then user's racket moves in the mentioned
direction unless its already completely at that side.

### Scenario: Movement of computer's racket is random

Given the game works efficiently and there is no error
in the game that may interrupt any functionality.

When the game starts as user hits START

Then the computer racket starts moving randomly
any direction.

### Scenario: Initially the Movement of ball is random

Given the game works efficiently and there is no error in
the game that may interrupt any functionality.

When the game starts as user hits START
and the ball is in center of the dashed white line.

Then the ball starts moving randomly in
any direction.

### Scenario: Ball changes direction when hits anything

Given the game works efficiently and there is no error
in the game that may interrupt any functionality,
and the ball is moving randomly.

When the ball hits the wall or the racket

Then the ball reflects back in other direction
with same angle that it strike.
