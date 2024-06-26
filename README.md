# Hangman Game

## Description

The Hangman Game project is a classic word-guessing game implemented in Python. The player tries to guess a hidden word by suggesting letters within a certain number of guesses. This version of Hangman includes features such as a dynamic display of the current guess, live tracking, and visual stages representing the hangman.

### Features

- **Word Selection**: A random word is selected from a predefined list.
- **Dynamic Display**: The game dynamically updates the display with correctly guessed letters.
- **Lives Tracking**: The player starts with a set number of lives, losing one for each incorrect guess.
- **Visual Stages**: The hangman stages are visually represented, showing progression with each incorrect guess.
- **Clear Function**: A function to clear the terminal screen for better readability.

### How to Use

1. **Clone the repository**:
   ```bash
   git clone https://github.com/your-username/hangman-game.git
   cd hangman-game
   ```

2. **Ensure Dependencies**:
   - The `words.py` file should contain a list named `word_list` with words for the game.
   - The `logo_stages.py` file should contain `logo` and `stages` for the game's visual representation.

3. **Run the game**:
   ```bash
   python hangman_game.py
   ```

4. **Gameplay**:
   - The player guesses letters one at a time.
   - Correct guesses update the display with the letter in the correct positions.
   - Incorrect guesses decrease the number of lives and update the hangman stages.
   - The game ends when the player guesses the word correctly or runs out of life.

### Example

```
Welcome to Hangman!
Guess a letter: e
_ e _ _ _ _
You guessed e, that's not in the word. You lose a life.
Remaining lives: 5
```

### Benefits

- **Interactive**: The game provides real-time feedback on guesses.
- **Visual Aid**: The stages of the hangman provide a clear visual representation of the remaining lives.
- **Educational**: Great for practicing vocabulary and spelling.

Enjoy playing the classic Hangman Game and improve your word-guessing skills!
