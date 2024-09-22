### The Prisoner's Dilemma

This is the most basic application of game theory. Consider the following:
- Player A and Player B are playing a game to win money.
- Each player must choose whether they want to "Split" the money or "Steal" the money.
- If both players "Split", they each get 3 coins.
- If one player chooses to "Split" and the other chooses to "Steal", the one who steals will receive 5 coins and the one who splits will receive none.
- If both players "Steal", they will receive 1 coin each.

Should each player "Split" or "Steal"? 

|              |         | Player B | Player B |
| ------------ | ------- | -------- | -------- |
|              |         | *Split*  | *Steal*  |
| **Player A** | *Split* | 3, 3     | 0, 5     |
| **Player A** | *Steal* | 5, 0     | 1, 1     |
Given the above and given that each player wants to maximize their gain, the following can be concluded:
- If Player B chooses to "Split" -> ​Player A's best choice would be to "Steal", since that gives them 5 coins instead of 3.
- If Player B chooses to "Steal" -> Player A's best choice would be to "Steal", since that gives then 1 coin instead of 0.

**Therefore, regardless of the choice Player B makes, Player A should always choose to "Steal", and vice versa.**

---
### Dominance

In the game above, for both players, the strategy of choosing "Split" is said to be  **strictly dominated** by that of choosing "Steal", since the latter is preferable in **all** scenarios. Rational players never play strictly dominated strategies.


