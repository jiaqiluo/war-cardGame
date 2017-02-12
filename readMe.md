#Object Oriented Programming
For this programs you will be applying OO techniques to creating a game. You will be creating a version of the card game WAR as described below with specific rules with a twist. Depending on the level of player (age for example), a variation is added called “Automatic” War where 2’s have special meaning and for advanced players, there is a version that adds spies (jokers). These versions will come into play for the second phase of the assignment with the user of dynamic binding. 

##The Overall Rules:

3. These cards create each player’s “downstack”
4. When the game begins, the top card is “revealed the” for a “battle” and higher card wins. The cards go to the bottom of the winner’s downstack.
  2. If a 2 is revealed (the lowest possible), it triggers an “Automatic” war.
  3. If there is a tie (or a 2), then a war takes place. Each player that had the same ranked card plays 4 cards where only the last one is “revealed” for “battle”. Again, the higher card wins and the cards to the bottom of the winner’s downstack. If there is a tie again, the process continues.
  4. There is one exception. When in a “war”, if one of the 3 down cards (that are not revealed) is a joker (a spy) then there is an automatic win for the player who had the joker. Think of this as you had a spy in the war and they caused a win!
  5. If there are two jokers in different player’s down cards (that are not revealed) in a war – then the war is over and no one wins. Everyone gets their cards back, at the bottom of their corresponding downstacks.




1. A **circular linked list of arrays**; every element of the array should be a “card” (suggestion: for the downstack)

