# wawa_game

Text-based game based on a card-game I used to play with my grandparents. 
The game is basically a word-snake game, and the goal is to be the first to get rid of all cards.

Gameplay:
- All players get dealt a hand with 7 initial cards. On each card there is a letter and a number. The number is used when the game has ended. 
- A first card "top card" is dealt
- Player 1 writes a word using their cards, starting with the "top card", removing the cards from their hand. The last letter in the word is now the new "top card"
- The next player does the same, using the new "top card" as initial letter. This goes on until a player has an empty hand. 
- If a player is unable to find a word, they are able to retrieve up to three new cards from the deck.
- When a player has won, the scores of all players are updated. The score is the sum of the numbers on the remaining cards The lower the score, the better. 
- The game can be played in many rounds
