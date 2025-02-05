The code now has the two palyer feature working where at the top it says whose turn it is and switches when a player gets a match wrong. There is a tracker for each player for how many matches they have and at the end the winner is displayed in a message. One change that was made was that the player1Matches and player2Matches counters now only update when the player finds a match. currentPlayer was also added to the UI display at the top of the game board. the checkForMatch function was changed by adding a check so that it would remain the current players turn if the player found a match because before it switched turns reagrdless of if a match was found. There was also a condition added to check was added at the end in case there was a tie.









