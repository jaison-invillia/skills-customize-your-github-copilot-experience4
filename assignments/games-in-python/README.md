# 📘 Assignment: Hangman Game Challenge

## 🎯 Objetivo

Create a Hangman game where players guess letters to reveal a hidden word before running out of attempts. This assignment will help you practice string manipulation, loops, conditionals, and random selection.

## 📝 Tarefas

### 🛠️ Random Word Selection

#### Description
Randomly select a word from a predefined list of words for the player to guess.

#### Requirements
Completed program should:

- Contain a predefined list of at least 10 words.
- Randomly select one word from the list at the start of the game.
- Ensure the selected word is hidden from the player.

### 🛠️ Letter Guessing and Progress Display

#### Description
Allow the player to guess letters and display their progress in the format `_ _ _` for unguessed letters.

#### Requirements
Completed program should:

- Accept letter guesses from the player.
- Display the current progress of the word after each guess.
- Ensure guessed letters are revealed in the correct positions.
- Handle both uppercase and lowercase inputs.

### 🛠️ Incorrect Guess Tracking

#### Description
Track the number of incorrect guesses remaining and end the game when attempts are exhausted.

#### Requirements
Completed program should:

- Start with a maximum of 6 incorrect guesses.
- Decrease the remaining attempts for each incorrect guess.
- Display the number of attempts remaining after each guess.

### 🛠️ Game End Conditions

#### Description
End the game when the player either guesses the word or runs out of attempts. Display appropriate messages for each outcome.

#### Requirements
Completed program should:

- Display a win message if the player guesses the word.
- Display a lose message if the player runs out of attempts.
- Reveal the correct word at the end of the game.
