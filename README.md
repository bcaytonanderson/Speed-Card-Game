Speed Simulator

This project comes from Week 5 of MakerSquare - Cohort 9 for our first "hackathon." We were to come up with an idea that could be reasonably be made presentable within 36 hours- no other restrictions were placed on the project and we were encouraged to work collaboratively. 

My class mate, Jeffrey Penkar, and worked together on our real collaborative project as developers-in-training. We had only just been introduced to JavaScript the week prior, and we decided it would be a great chance for us to get more experience with new material. For that reason, we wanted to build a single page app that was based almost exclusively on JavaScript. Simulating a card game gave us the perfect opportunity to explore the possibilities of JavaScript, to become more familiar with events and listeners, and to work with jQuery and DOM manipulation. We also decided to implement an AI with scalable difficulty, two sets of game controls to allow two players to play on one computer, and a persistent leaderboard using Firebase.

The code has not been altered or refactored since the hackathon wrapped up, and I will leave it intact for posterity.

To play the game:
The goal of the game is for the player to clear his deck before their opponent. Each player is dealt 20 cards, and the game board has 4 face-down piles: the piles on the inside are the playable cards- only cards with values which equal +/-1 to these play cards may be played (no doubles); the cards on the outside are utilized if both players have run out of plays. A player may only have 5 cards in their hand at a time, and may draw a card any time he has less than 5.

Against the AI, Player 1 controls the lower set of cards with the mouse. The AI difficult level can be set at the beginning of the game, and it decides how quickly the AI will make its moves. Or, the option for 2 players is available where Player 1 controls the lower cards with the mouse, and Player 2 controls the upper cards with the keyboard.

Player 1: Left-clicking a card in your hand will attempt to play that card on the left Play Card. Right-clicking will attempt to play on the right Play Card. Clicking the deck in the lower left corner will draw cards.

Player 2: The five cards in Player 2's hand are mapped to the A, S, D, F, and G keys respectively. Player 2 plays a card by pressing the corresponding button and the either the left or right arrow key to play on the corresponding Play Card. The up arrow will draw cards.

There is room for improvement- such as our shuffling algorithm, which seems to put triples and quads of the same card value into a player's hand- but for having only known JavaScript's basics for about a week and a half, and for only beeing 4.5 weeks into the MakerSquare program, I like to think that it's a good attempt!
