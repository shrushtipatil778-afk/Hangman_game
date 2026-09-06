# 🎮 Hangman Game – Python

A simple text-based **Hangman Game** developed using Python as part of my **CodeAlpha Python Programming Internship**.

## 📌 Project Overview

This project is a console-based Hangman game where the player has to guess a randomly selected word one letter at a time.

The game provides a maximum of **6 incorrect guesses**. The player wins when all the letters of the selected word are guessed correctly.

## ✨ Features

- 🎲 Random word selection
- 🔤 Guess the word one letter at a time
- ❌ Maximum 6 wrong guesses allowed
- ✅ Displays correct guesses
- ⚠️ Handles invalid input
- 🔁 Prevents repeated letter guesses
- 🏆 Displays a winning message
- 😔 Displays the correct word when the player loses

## 🛠️ Technologies Used

- **Python**
- `random` module
- While loop
- If-else statements
- Strings
- Lists
- User input/output

## 📋 How the Game Works

1. The program randomly selects a word from a predefined list.
2. The selected word is displayed as underscores.
3. The player enters one letter at a time.
4. If the letter is correct, it is revealed in the word.
5. If the letter is incorrect, the wrong-guess count increases.
6. The player can make a maximum of 6 incorrect guesses.
7. The game ends when:
   - The player guesses the complete word successfully, or
   - The player reaches 6 incorrect guesses.

## ▶️ How to Run

### Step 1: Install Python

Make sure Python is installed on your computer.

### Step 2: Clone the Repository

```bash
git clone <YOUR_GITHUB_REPOSITORY_LINK>
