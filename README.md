Your README content looks clear and informative! Here are a few suggestions to refine and polish it further:

---

# Wordly Auto Solver Chrome Extension

## Description
This Chrome extension auto-solves Wordle problems (5-letter words) specifically for [Wordly](https://wordly.org/). The extension may or may not work with other Wordle websites. On average, this extension can solve a problem in 3-4 tries.

This is a side project that I’ve been working on for the past 2 days (as of September 15).

## Limitations
- **Word List Dependency**: This solver relies on a predefined list of words. If the word problem does not exist in the list, the solver may not be able to solve it. However, it has successfully solved most problems encountered.
- **Word Length**: Currently, this solver only handles 5-letter word problems.
- **Word Lists**: The extension includes both 2000-word and 5000-word lists. By default, it uses the 2000-word list to maximize speed.

## Installation
1. Download and unzip the folder.
2. Open Chrome.
3. Navigate to `chrome://extensions/`.
4. Enable **Developer Mode**.
5. Click **Load unpacked**.
6. Select the unzipped folder.
7. Use the extension specifically on [Wordly](https://wordly.org/).

## Optional: Using the 5000-Word List
1. Open `word.py` and change the line:
   ```python
   with open(f'{letters}_letter_words.txt') as file:
   ```
   to:
   ```python
   with open(f'{letters}_letter_words_long.txt') as file:
   ```
2. Run the Python script.

## Optional: Adding Custom Words
1. Edit the `.txt` files to include your custom words.
2. Run the Python script to update the word lists.

## Notes
- Ensure that the extension is used exclusively on Wordly to avoid issues.
- If you encounter any problems or need further assistance, please refer to the issues section of this repository.

---

Feel free to adjust any sections according to your needs or preferences! This README should provide users with a clear understanding of the extension's purpose, installation process, and optional configurations.
