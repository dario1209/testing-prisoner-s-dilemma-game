# testing-prisoner-s-dilemma-game
This smart contract defines a Prisoner's Dilemma game with two players. The player1 and player2 addresses are defined in the constructor, and the play function allows each player to make their choice (either 0 or 1) for each round of the game. The startGame function can only be called by player1 to start the game.

The getScore function calculates the score for each player based on their choices. The scores are returned as an array, with the first element being the score for the player who called the function and the second element being the score for the other player.

The game ends when one player reaches a score of 2 or higher. The getWinner function returns the address of the player with the highest score at the end of the game.

Note that this is a simple example and can be modified to fit more complex versions of the Prisoner's Dilemma game.
