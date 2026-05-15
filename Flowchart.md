# 🎮 Rock Paper Scissors Game - Flowchart

```mermaid id="mukm4g"
flowchart TD

    A([Start]) --> B[Read Number Of Rounds]

    B --> C[Start Round Loop]

    C --> D[Player Chooses Stone / Paper / Scissors]

    D --> E[Computer Generates Random Choice]

    E --> F{Compare Choices}

    F -- Same Choice --> G[Round Result = Draw]

    F -- Player Wins --> H[Round Result = Player Wins]

    F -- Computer Wins --> I[Round Result = Computer Wins]

    G --> J[Increase Draw Counter]
    H --> K[Increase Player Counter]
    I --> L[Increase Computer Counter]

    J --> M[Display Round Result]
    K --> M
    L --> M

    M --> N{More Rounds?}

    N -- Yes --> C

    N -- No --> O[Display Final Game Results]

    O --> P{Play Again?}

    P -- Yes --> B

    P -- No --> Q([End])
```
