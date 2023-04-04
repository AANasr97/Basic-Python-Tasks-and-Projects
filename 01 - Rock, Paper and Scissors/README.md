# Rock-Paper-Scissors Game

This is a simple implementation of the classic game "Rock-Paper-Scissors" using Python. The code prompts the user to choose between rock, paper, or scissors and then plays a round against the computer.

## How to play

1. Clone or download the repository
2. Open the terminal/command prompt and navigate to the project directory
3. Run the `01 - Rock, Paper and Scissors.ipynb`
4. Follow the prompts to play the game

## Game rules

- Rock beats Scissors
- Scissors beats Paper
- Paper beats Rock

## Code explanation

The `01 - Rock, Paper and Scissors.ipynb` file starts by importing the `random` module. Then, it defines three variables `rock`, `paper`, and `scissors` which are strings representing the ASCII art of the corresponding game option.

Next, the code enters a loop which continuously prompts the user to play the game until they choose to stop. Within this loop, another loop is used to prompt the user to choose either 'R' for rock, 'P' for paper, or 'S' for scissors. If the user's input is not one of these options, an error message is displayed, and the prompt is repeated until a valid input is entered.

After the user makes their choice, the program uses the `random` module to generate a random choice for the bot. The program then prints out the choices of both the player and the bot.

Finally, the code compares the player's choice with the bot's choice and determines the winner of the game. If the game is a tie, it prints a message indicating this. If the player wins, it prints a message indicating this, and if the player loses, it prints a message indicating this.

The user is then prompted to play again or exit the program. If the user chooses to play again, the game restarts, otherwise, the program exits.

Overall, this code is a fun and interactive game that demonstrates basic programming concepts such as loops, conditionals, and user input/output.

### Done By:
#### Ahmed NasrElDin