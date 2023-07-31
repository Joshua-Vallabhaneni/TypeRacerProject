# TypeRacerProject

TypeRacer is a Java program that provides a typing game where the user can improve their typing speed and accuracy by typing a given prompt as fast and accurately as possible. The user will see a text prompt on the screen, and they have to type the words correctly and press the space bar to move on to the next word.

**Note**: The game only terminates when the user reaches the end of the prompt and presses the space bar.

## How to Use

1. Download or clone the TypeRacer.java file and any necessary text files (e.g., "Prompts.txt" and "Stats.txt") for prompts and statistics recording.

2. Compile and run the program using a Java compiler, such as `javac TypeRacer.java` followed by `java TypeRacer`.

3. Once the program starts, you'll see a text prompt displayed at the top. Start typing the words as accurately and quickly as possible.

4. Press the space bar after completing each word to move on to the next one. The program will highlight the word in yellow while you're typing, turn it green if it's correct, or red if it's incorrect.

5. The program will display your current Words Per Minute (WPM) and Accuracy percentage at the bottom of the screen.

6. The computer will also simulate typing the prompt at 60WPM for competitive comparison.

7. The game will end automatically when you finish typing the entire prompt. The program will record your final WPM and Accuracy into the "Stats.txt" file.

## Dependencies

TypeRacer requires Java and the Swing library to run.

## Project Structure

- `TypeRacer.java`: The main Java file that contains the TypeRacer class, responsible for creating the graphical elements and managing the game logic.
- `AnalyzerForText.java`: A helper class that reads a random line from the "Prompts.txt" file and returns the words of the prompt as a string array.
- `Getter.java`: A helper class that stores information about individual words in the prompt, including their start and end positions, highlight token, and the word itself.
- `StatRecorder.java`: A helper class responsible for recording the final WPM and Accuracy into the "Stats.txt" file.

## License

This project is licensed under the MIT License. Please refer to the LICENSE file for more information.

## Credits

- The DefaultHighlighterPainter constructor code snippet researched from docs.oracle.com.
- The concept and implementation of the TypeRacer game are created by [Pranavh Joshua Vallabhaneni] 
