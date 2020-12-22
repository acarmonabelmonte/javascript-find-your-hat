# Find Your Hat

In this project, you’ll be building an interactive terminal game. The scenario is that the player has lost their hat in a field full of holes, and they must navigate back to it without falling down one of the holes or stepping outside of the field.

Watch this gif to get a sense of what you’ll be building:

![game-video](https://content.codecademy.com/PRO/independent-practice-projects/find-your-hat/find-your-hat-demo.gif)

Your game should be playable by users. In order to facilitate this, build out the following behavior:

- When a user runs **main.js**, they should be prompted for input and be able to indicate which direction they’d like to “move”.
- After entering an instruction, the user should see a printed result of their current field map with the tiles they have visited marked with `*`. They should be prompted for their next move.

This should continue until the user either:

1. Wins by finding their hat.
2. Loses by landing on (and falling in) a hole.
3. Attempts to move “outside” the field.

When any of the above occur, let the user know and end the game.
