# Yahtzee Game

A console-based version of the popular **Yahtzee** game built using **C#**. This game allows players to roll dice, choose scoring categories, and calculate their scores based on classic Yahtzee rules. Multiple players can play, and the game keeps track of scores and determines the winner after all rounds.

## Features
- **Turn-based gameplay**: Supports 1 to 4 players, with each player taking turns to roll dice and select categories.
- **Dice rolling mechanics**: Players roll 5 dice, with up to two re-rolls per turn.
- **Scoring categories**: Includes classic Yahtzee scoring options like Ones, Twos, Full House, Small Straight, Large Straight, and Yahtzee.
- **Score calculation**: Automatically calculates scores based on the dice rolled and chosen category.
- **Multiplayer support**: Play with up to 4 players in a single game.
- **Random dice rolling**: Simulates real dice rolling using a random number generator.

## Technologies Used
- **C#**
  
## How to Play
1. Each player rolls 5 dice.
2. Players can re-roll any number of dice up to 2 times.
3. After rolling, players choose a scoring category (e.g., Full House, Large Straight, etc.).
4. The game automatically calculates the score for that category.
5. Play continues for 13 rounds, and the player with the highest score at the end wins.

## How to Run the Project
1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Yahtzee-Game.git
   ```
2. Open the project in **Microsoft Visual Studio**.
3. Build the project by selecting **Build > Build Solution**.
4. Run the project by pressing **F5** or selecting **Debug > Start Debugging**.

## Scoring Categories
- **Ones, Twos, Threes, Fours, Fives, Sixes**: Score the sum of the chosen number on the dice.
- **Three of a Kind**: If three dice show the same number, score the sum of all dice.
- **Four of a Kind**: If four dice show the same number, score the sum of all dice.
- **Full House**: Score 25 points for a pair and three of a kind.
- **Small Straight**: Score 30 points for four sequential dice.
- **Large Straight**: Score 40 points for five sequential dice.
- **Yahtzee**: Score 50 points for five dice of the same number.
- **Chance**: Score the sum of all dice.

## Future Improvements
- Add a GUI for better user interaction and game display.
- Implement network-based multiplayer mode for remote play.
- Add more game variations to increase complexity and replayability.

## Contributions
Feel free to fork this repository, submit issues, or make pull requests to contribute to this project!

---
