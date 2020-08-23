# Interaction Sequences

## Startup Sequence

```mermaid
sequenceDiagram
User->>+GUI.md: clicks on game icon
GUI.md-->>-User: asks  for name
User->>+GUI.md: enters name
GUI.md-->>-User: start of exit the game
User->>+GUI.md: clicks on exit
GUI.md-->>-User: "Do you want to exit the game? yes or no"
User->>+GUI.md: "yes"
GUI.md-->>-User: game ends
```

## Movement Initiation

```mermaid
sequenceDiagram
GUI.md->>+movement-of-ball-and-racket.md: user click on "START"
GUI.md->>+movement-of-ball-and-racket.md: black background, white ball in center, rackets in middle
movement-of-ball-and-racket.md-->>-GUI.md: ball starts moving randomly in any direction initially
GUI.md->>+movement-of-ball-and-racket.md: ball hits any wall or rackets
movement-of-ball-and-racket.md-->>-GUI.md: ball reflects
```

## One score

```mermaid
sequenceDiagram
score-keeper.md-->>+movement-of-ball-and-racket.md: score 0-0 of human-computer
movement-of-ball-and-racket.md->>+score-keeper.md: ball hits wall behind user's racket
score-keeper.md-->>-movement-of-ball-and-racket.md: increment computer's point by 1
movement-of-ball-and-racket.md->>+score-keeper.md: ball hits wall behind computer's racket
score-keeper.md-->>-movement-of-ball-and-racket.md: increment user's point by 1
score-keeper.md-->>+movement-of-ball-and-racket.md: Declares the winner's name
Note over score-keeper.md, movement-of-ball-and-racket.md: Anyone scores 5 points
```
