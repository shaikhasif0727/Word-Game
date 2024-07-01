# Wordle Game with Jetpack Compose

This project is a simple implementation of the popular Wordle game using Android's Jetpack Compose. The game includes a vertically oriented keyboard in a grid layout with a back button and a grid for displaying guesses.

## Features

- Guess the word within 5 attempts.
- Vertical keyboard layout with keys arranged in a grid.
- Large back button for deleting the last entered letter.
- Visual feedback for correct, present, and absent letters.

## Screenshots

![Screenshot 1](screenshots/screenshot1.png)
![Screenshot 2](screenshots/screenshot2.png)

## Installation

1. Clone the repository:
    ```sh
    git clone https://github.com/shaikhasif0727/Word-Game.git
    ```

2. Open the project in Android Studio.

3. Build and run the project on an emulator or physical device.

## Usage

1. Launch the app on your Android device.
2. Use the on-screen keyboard to input your guesses.
3. Press the back button to delete the last letter if needed.
4. Press "Submit" to check your guess.
5. The game will provide feedback on the correctness of your guess.

## Code Structure

- `MainActivity.kt`: The main activity hosting the Compose UI.
- `GameState.kt`: Data class to manage the state of the game.
- `GuessBoard.kt`: Composable function to display the grid of guesses.
- `GridKeyboard.kt`: Composable function to display the keyboard with a large back button.
- `CheckGuess.kt`: Logic to check the user's guess against the target word.

## Contributing

Contributions are welcome! Please fork the repository and submit a pull request with your changes.

1. Fork the repository.
2. Create a new branch:
    ```sh
    git checkout -b feature-branch
    ```
3. Make your changes.
4. Commit your changes:
    ```sh
    git commit -m 'Add some feature'
    ```
5. Push to the branch:
    ```sh
    git push origin feature-branch
    ```
6. Open a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## Contact

If you have any questions or feedback, please contact me at [].

---

Happy coding!
