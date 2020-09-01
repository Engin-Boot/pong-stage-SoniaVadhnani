# Movement of Racket

## Feature

This module is responsible asking user
for its credentials so that the progress
could be maintained.

## Acceptance Criteria

### Scenario: Ask for login with credentials

Given the game works efficiently and there is no error
in the game that may interrupt any functionality.

When the user taps on the game icon
And the game initializes

Then ask for user to sign in with
google account
or sign up/register or play as guest.

### Scenario: Ask for google credentials

Given the game has asked for credentials

When the user selects login with
google account.

Then ask for google account username
and password.

### Scenario: Ask for new user credentials

Given the game has asked for credentials

When the user selects sign up/ register

Then ask for user credentials like
full name, age, username, password.

### Scenario: Ask for only name

Given the game has asked for credentials

When the user selects login as guest

Then ask for only the name of user.
