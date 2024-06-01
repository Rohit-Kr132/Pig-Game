## Pig Game

This is a multiplayer Pig Game built using HTML, CSS, and JavaScript. Two players take turns rolling two dice and accumulating points. The first player to reach 100 points wins the game.

### Rules of the Game

1. **Turn Structure:**
    * Each player takes turns rolling two dice.
    * The sum of the dice is added to the player's current turn score.
    * Rolling a 1 on any die resets the player's current turn score to 0 and ends their turn.
    * Players can choose to "Hold" after any roll. This adds their current turn score to their total score and ends their turn.
2. **Winning:**
    * The first player to reach a total score of 100 points wins the game.

### Features

* **Multiplayer:** Supports gameplay for two players.
* **Dice Rolling:** Simulates rolling two dice with random numbers.
* **Turn Tracking:** Keeps track of each player's current turn score and total score.
* **Hold Button:** Allows players to hold their turn score and pass the dice.
* **Visual Interface:** Displays the dice, player scores, and current turn information.
* **Responsive Design:** Adapts to different screen sizes for optimal viewing on any device.

### Technologies Used

* HTML: Provides the structure and content of the web page.
* CSS: Styles the game interface for visual appeal and user experience.
* JavaScript: Handles user interactions, dice rolls, scorekeeping, and game logic.

### Getting Started

1. Clone the repository:

```
git clone https://github.com/Rohit-Kr132/Pig-Game.git
```

2. Open the `index.html` file in a web browser.

3. Start playing with your friends!

### Contributing

Feel free to fork this repository and contribute to the project. Pull requests are welcome!

### Additional Notes

* This is a basic implementation of Pig Game. You can extend it with additional features such as:
    * Setting a custom winning score.
    * Implementing a "Double Down" option to potentially double the current turn score but risk losing everything if a 1 is rolled.
    * Adding sound effects and animations for a more engaging experience.
