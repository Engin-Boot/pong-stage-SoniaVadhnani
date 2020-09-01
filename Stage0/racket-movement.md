# Movement of Racket

## Feature

This module is responsible left and right
movement of rackets.

## Acceptance Criteria

### Scenario: Move user's racket according to user's input

Given two buttons left and right under user's racket
which works efficiently and it takes 6 left taps
to reach completely to the left from complete right and
vice versa or the user can slide the racket.

When user taps on any of the button or slides
the racket

Then user's racket moves in the mentioned
direction unless its already completely at that side.

### Scenario: Movement of computer's racket is random

Given the game works efficiently and there is no error
in the game that may interrupt any functionality.

When the game starts as user hits START

Then the computer racket starts moving randomly
any direction
And it's position is updated by "continuous_loop" module.
