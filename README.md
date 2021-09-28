# OpenTag Task

### Implements application that calculates an exchange rate

### Requirements
* When you provide two currency codes you need to receive how much it costs to exchange one currency for another.
    - Example: When we provide these `CAD CHF` codes we expect to receive something similar to `0,73`
* We also expect immediately after the exchange rate to have a sign that shows us the direction of average discrepancy in the last 10 calculation of the same pair of currencies relative to the current calculation
    - Example `0,73 ↑` or `0,73 ↓` or `0,73 -`

### Rules of the game:
* Code in PHP, ideally using the Symfony framework
* You're free to choose any storage mechanism you wish We expect to be able to run the application locally just running docker-compose, with no external dependencies required to run it.

### Bonus
* Full tests coverage
* UI
