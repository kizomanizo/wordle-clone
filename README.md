# Wordle Clone

A simple browser-based Wordle clone built with HTML, CSS, and JavaScript.

## Features

- 6 tries to guess a random 5-letter English word
- Animated flip and color feedback for each letter (green, amber, grey)
- Keyboard and button input support
- Tracks number of tries, wins, and losses
- Stylish stats table and dynamic tries counter
- Responsive design for desktop and mobile

## How to Play

1. Type letters using your keyboard or click the squares to fill in your guess.
2. Press **Enter** or click the **Enter** button to submit your guess.
3. Use **Delete** or **Backspace** to remove the last letter.
4. You have 6 tries to guess the correct word.
5. Green means correct letter and position, amber means correct letter wrong position, grey means letter not in the word.
6. Stats are shown below the buttons.

## Development

- All logic is in a single `index.html` file.
- The word dictionary is hardcoded in JavaScript.
- To change the dictionary, edit the `dictionary` array in the script section.
- To reset the game, click the **RESET** button.

## Customization

- You can style the game by editing the CSS in the `<style>` block.
- To add more words, update the `dictionary` array.

## License

MIT License

---

Made with ❤️ using vanilla
