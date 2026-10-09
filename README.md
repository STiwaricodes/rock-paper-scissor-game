# Rock Paper Scissor Game

A browser-based Rock Paper Scissor game built using HTML, CSS, and JavaScript. Play against the computer, view both choices, and track your wins, losses, and draws through a live scoreboard.

## Features

- Play Rock, Paper, or Scissor against the computer.
- Computer generates a random choice for each round.
- Display the player's and computer's choices using emojis.
- Automatically determine the winner of each round.
- Track player wins, computer wins, and draws.
- Reset button to reset the scoreboard and choices.
- Responsive user interface for desktop, tablet, and mobile screens.
- Dark-themed design with interactive buttons and visual effects.

## Technologies Used

- **HTML5** — Game structure and interface.
- **CSS3** — Styling, responsive layout, and button effects.
- **JavaScript** — Game logic, random computer choices, score tracking, and event handling.
- **Google Fonts (Poppins)** — Typography.

## Game Rules

- **Rock beats Scissor**
- **Scissor beats Paper**
- **Paper beats Rock**
- If both choose the same option, the round is a draw.

## How to Play

1. Open the game in your browser.
2. Choose Rock, Paper, or Scissor.
3. The computer randomly selects its move.
4. View both choices and the round result.
5. Continue playing to increase your score.
6. Click **Reset** to reset the scoreboard and choices.

## Project Structure

```text
rock-paper-scissor/
├── index.html
├── style.css
├── script.js
└── README.md
```

**Note:** The current HTML file contains the CSS and JavaScript inline. If you want to use separate `style.css` and `script.js` files, move the respective code into those files and update the HTML references.

## How to Run Locally

1. Clone or download the repository.
2. Open `index.html` in your web browser.
3. Start playing—no package installation or build tools are required.

## Current Limitations

- Scores reset when the page is refreshed.
- There is no maximum score or best-of series mode.
- The reset button resets the scores and player choices, but the result message is not currently reset.

## Future Improvements

- Add a best-of-5 or best-of-10 game mode.
- Save scores using Local Storage.
- Add sound effects and animations.
- Highlight the winner after each round.
- Improve accessibility and keyboard support.

## License

This project is created for learning and practice purposes. Add a formal license if you plan to distribute it publicly.