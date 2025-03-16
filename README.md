This script provides a comprehensive typing practice application with various features including dark mode, difficulty levels, word skipping, and more. Below is a summary of the key components and their functionalities:

1. Utility Functions:
    - `$`: A shorthand function for `document.querySelector`.
    - `setDomText`: Sets the text content of a DOM element.
    - `setDomStyle`: Sets the style property of a DOM element.

2. Audio Utilities:
    - `audio.create`: Creates an audio object for a given word.
    - `audio.play`: Plays an audio object and returns a promise that resolves when the audio ends.
    - `audio.playTwice`: Plays an audio object twice.

3. Animation Handling:
    - `transitionAnimation`: Handles the transition animation for DOM elements.

4. Local Storage Utilities:
    - `storage.get`: Retrieves a value from local storage.
    - `storage.set`: Sets a value in local storage.
    - `storage.getBool`: Retrieves a boolean value from local storage.
    - `storage.saveToList`: Saves an item to a list in local storage.

5. Formatting Utilities:
    - `format.time`: Formats seconds into a `MM:SS` string.
    - `format.percentage`: Calculates the percentage of a value relative to a total.
    - `format.speed`: Calculates typing speed in characters per minute.

6. Word Utilities:
    - `wordUtils.selectByLevel`: Selects a specified number of words based on difficulty level.
    - `wordUtils.highlightTyped`: Highlights the typed portion of a word.

7. State Management:
    - `state`: An object that holds the current state of the application, including word index, typed characters, selected words, and more.

8. DOM Elements Cache:
    - `e`: An object that caches frequently accessed DOM elements.

9. Initialization:
    - `init`: Initializes the application, resets state, and starts the timer.

10. Timer Update:
     - `updateTimer`: Updates the timer and typing speed display.

11. Word Display Update:
     - `updateWordDisplay`: Updates the display of the current, previous, and next words.

12. Word Navigation:
     - `advanceToNextWord`: Advances to the next word.
     - `skipWord`: Skips the current word.
     - `goBackWord`: Goes back to the previous word.
     - `wordTransition`: Handles the transition animation between words.

13. Typing Completion:
     - `handleTypingComplete`: Handles the completion of typing practice.

14. Typing Handling:
     - `handleTyping`: Handles keypress events for typing.

15. Statistics Update:
     - `updateStats`: Updates the typing statistics display.

16. Mode Toggles:
     - `toggleDarkMode`: Toggles dark mode.
     - `updateDifficulty`: Updates the difficulty level.
     - `toggleHideWord`: Toggles the word hiding mode.
     - `toggleSkipWordsMode`: Toggles the skip words mode.
     - `clearSkippedWords`: Clears the list of skipped words.

17. Event Listeners:
     - Adds event listeners for various UI elements and keyboard events to handle user interactions.
