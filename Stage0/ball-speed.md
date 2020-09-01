# Movement of Racket

## Feature

This module is responsible for the speed of ball.

### Scenario: Ball collide with racket and racket is still

Given The game is working efficiently

When ball hits the racket
And the racket is still

Then no change in speed

### Scenario: Ball collide with racket with same direction

Given The game is working efficiently

When ball hits the racket
And the racket moves in same direction
the ball is bounced back

Then speed of ball is increased a little

### Scenario: Ball collide with racket with opposite direction

Given The game is working efficiently

When ball hits the racket
And the racket moves in opposite direction
the ball is bounced back

Then speed of ball is decreased a little
