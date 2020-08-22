# GUI

## Feature

This module is responsible for the appearance of the game,
from background color or image to shape and size of the ball and rackets. (So far the game is for single user.)

## Acceptance Criteria

### Scenario: Initial interface

Given the game works efficiently and there is no
error in the game that may interrupt any functionality.

When user initializes the game by clicking on the game icon.

Then there will be a field that asking for user's name
with already filled name as "HUMAN", a start button
and a quit button.

### Scenario: Interface after the user hits START

Given the initial interface that has start
button and exit button and both works correctly

When user clicks on START

Then the game starts with user's and computer's racket
on middle of their sides of color black and ball of color red
on the user's racket, with the background black,
a dashed white line that denotes the middle of the court,
and two buttons "Left arrow" in left side and "Right arrow"
in right side are
under the user's racket.

### Scenario: Ask if user want to exit the game when user hits EXIT

Given the initial interface that has start
button and exit button and both works correctly

When user hits exit to quit the game.

Then a popup appears asking "Do you want
to exit the game?" with two options "yes" or "no".

### Scenario: Exit when user wants to exit

Given the initial interface that has exit button
which works correctly

When user doesn't want to play anymore and
hits exit and yes to quit the game

Then the game exits.
