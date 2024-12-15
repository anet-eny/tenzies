# Tenzies

Tenzies is a simple dice game where you roll dice to try to get all of them to show the same number. The goal is to roll until all dice match, and you can hold a die in place by clicking on it. Once all dice are the same, you win the game! This project was developed as part of the Scrimba curriculum.

## Features

- **Rolling Dice**: Roll up to 10 dice, with the ability to hold any dice by clicking on them.
- **Game Reset**: When all dice are the same, a button allows you to start a new game.
- **Confetti Effect**: A confetti animation is shown when the game is won.
- **Accessibility**: Uses `aria-live` to notify screen reader users when they win.

## Key Learnings

- **useState Hook**: Used `useState` to manage the state of the dice in the game, allowing for dynamic updates when a die is rolled or held.

- **useRef Hook**: Used `useRef` to reference the "New Game" button, enabling focus management when the game is won.

- **useEffect Hook**: Utilized `useEffect` to trigger side effects, such as focusing the "New Game" button after the game is won, ensuring a smooth user experience.

- **Conditional Rendering**: Applied conditional rendering to display the confetti animation and win message only when the game is won, providing dynamic feedback to the user.

## View Project
https://anet-eny.github.io/tenzies/