# Score Keeper

## Feature

This module is responsible keeping the
score count of both the user and the computer,
and tell who won the game. At this time the winning
score is 5.

## Acceptance Criteria

### Scenario: Keeping the count of computer's score

Given the game works efficiently and there is no error in the
game that may interrupt any functionality.

When the user's racket misses the ball
and the ball hits the wall behind user's racket
and computer's score is not 4.

Then increment computer's score by 1.

### Scenario: Keeping the count of user's score

Given the game works efficiently and there is no error in the
game that may interrupt any functionality.

When the computer's racket misses the ball
and the ball hits the wall behind computer's racket
and user's score is not 4.

Then increment user's score by 1.

### Scenario: Declare winner at score equals 5

Given the game works efficiently and there is no error in the
game that may interrupt any functionality.

When ball hits any wall behind the racket
and opponent's score is 4.

Then increment opponent's score to 5
and show a box with "<winner's name> won
the game", below which a box asking question
"wanna play again?" with options yes or no.
