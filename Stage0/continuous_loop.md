# Continuous Loop

## Feature

This loop runs continuously during the game
and update concerned modules about the ball and
racket position in every one-tenth second.

## Acceptance Criteria

### Scenario: Update ball-movement about ball's position

Given The game is working efficiently

When the user hits start
And the ball is in center

Then randomly move ball in any direction
And update ball-movement module about the
position of ball every one-tenth second.

### Scenario: Update racket-movement about racket's position

Given The game is working efficiently

When the user hits start
And rackets are in middle

Then update the "racket-movement" about
the position of racket every one-tenth second.

### Scenario: Ball hits wall behind racket

Given The game is working efficiently

When the balls hits the wall behind
the racket

Then update "score-keeper" about it.
