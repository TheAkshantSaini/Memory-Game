# Memory Game

This is a simple memory game implemented using HTML, CSS, and JavaScript. The goal of the game is to match pairs of cards with the same emoji.

## How to Play

1. Open the `index.html` file in your web browser.

2. Click on the "Start" button to begin the game.

3. Click on any card to flip it.

4. Try to find the matching pair of cards with the same emoji.

5. If the cards match, they will remain face up. If they don't match, they will flip back after a short delay.

6. Continue flipping cards and finding matching pairs until all cards are matched.

7. Once all cards are matched, a "You won!" message will be displayed, showing the number of moves and the time taken to complete the game.

8. You can click the "Start" button again to play a new game.

## Technologies Used

- HTML
- CSS
- JavaScript

## Update History

### Update V1.1 - 17-07-2023

#### HTML Changes:
- Added a `<link>` tag to include a favicon for the web app.
- Added `<meta>` tags for the description and keywords to improve SEO.
- Added a credits section at the bottom to display the names of Pralin Khaira and Akshant Saini.

#### CSS Changes:
- Updated the styling for the game container using flexbox to center it vertically and horizontally.
- Used CSS variables for primary, secondary, tertiary, and background colors for easier customization.
- Added media queries for responsive design.
- Updated the font-family declaration to include fallback fonts for better compatibility.

#### JavaScript Changes:
- Wrapped the code in an IIFE (Immediately Invoked Function Expression) to encapsulate the code and avoid polluting the global namespace.
- Updated the `generateGame` function to generate the cards HTML using a separate function `generateCardsHTML` for better code organization.
- Added a timer that counts the time taken to complete the game and displays it in the UI.
- Added a move counter that keeps track of the total number of moves made to complete the game and displays it in the UI.
- Modified the `startGame` function to check if the game has already started before starting a new game.
- Added the `abortGame` function to reset the game state and board when the "Abort" button is clicked.
- Modified the `attachEventListeners` function to listen for the "abort" button click event.
- Modified the `attachEventListeners` function to call the `updatePlayerInput` function when the "start" button is clicked.

#### Overall Improvements:
- Organized the code by separating HTML, CSS, and JavaScript into separate files.
- Added appropriate comments to enhance code readability and maintainability.
- Added a favicon, meta tags, and credits to improve the web app's SEO and user experience.
- Made the game UI more responsive by using media queries.
- Used CSS variables for easier customization of colors.
- Encapsulated JavaScript code within an IIFE to avoid global namespace pollution.
- Refactored the code by breaking down the `generateGame` function into smaller, reusable functions.
- Updated the font-family declaration in CSS to include fallback fonts.
- Updated the timer and move counter in the JavaScript code to display the elapsed time and move count in the UI.


## Screenshots:

### Base version (V1.0)
![Base Version 1.0](https://i.imgur.com/B06d1oU.png)
![Base Version 1.0](https://i.imgur.com/awBXS5D.png)

### Update V1.1
![Update V1.1](https://i.imgur.com/fG0Grof.png)
![Update V1.1](https://i.imgur.com/Tvz6rRH.png)

## Credits

- The game was created by Akshant Saini. Feel free to customize and modify the code to suit your needs.

- The project update was designed by [Pralin Khaira](https://github.com/pralinkhaira/) (Update V1.1).

- Emoji icons used in the game are sourced from [EmojiOne](https://emojione.com/) and [Twemoji](https://twemoji.twitter.com/).

### Contributors:
- Akshant Saini
- [Pralin Khaira](pralinkhaira.github.io)

## License

This project is licensed under the [MIT License](LICENSE).
