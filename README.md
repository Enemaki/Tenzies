## Tenzies: A Dice Game with React Fundamentals

Tenzies is a fun and challenging dice game built with React to showcase the core concepts of state variables (`useState`), the `useEffect` hook, and conditional rendering. Roll the dice, hold those that contribute to a tenzi (all the same value), and see if you can achieve it in the fewest rolls\!

### Mastering Core React Principles

This project highlights the importance of three fundamental React features:

  * State Variables (useState): We utilize `useState` to manage the evolving state of the game, including the current dice values, held dice, and the number of rolls.
  * useEffect Hook: The `useEffect` hook comes into play to reset the game when necessary and potentially store game data in the future.
  * Conditional Rendering: Different UI elements are rendered based on the game state, such as showing held dice and displaying victory or defeat messages.

### Rolling Your Way to Tenzi Glory

Get ready to test your luck and strategy with Tenziestenzies, featuring:

  * Five Dice: Roll five dice to see what numbers come up.
  * Hold and Reroll: Hold any dice you want to keep and reroll the rest to try and form a tenzi.
  * **Track Your Rolls: Keep an eye on the number of rolls you've taken.
  * Win or Lose: Celebrate victory if you achieve tenzi, or try again if you run out of rolls.

Note: This project focuses on core React concepts and basic game mechanics. Future updates could include a timer, sound effects, and a high score system.

### Technologies Used

  * Frontend: HTML, CSS, Javascript
  * Framework: Vite React ([vitejs.dev](https://www.google.com/url?sa=E&source=gmail&q=https://vitejs.dev/))

### Setting Up Your Tenzi Challenge

1.  Clone the Repository:

<!-- end list -->

```bash
git clone https://github.com/your-username/tenziestenzies.git
```

2.  Install Dependencies:

<!-- end list -->

```bash
npm install
```

3.  Run the App:

<!-- end list -->

```bash
npm run dev
```

This will start the development server and open the app in your default browser at http://localhost:5173/.

### Understanding the Code

Explore the project code to see how state variables, `useEffect`, and conditional rendering power the game:

  * Dice component: Manages individual dice values and toggles their held state.
  * Roll button: Triggers a state update to reroll the dice (except for held ones).
  * Hold functionality: Updates the held state of a die when clicked.
  * Game status display: Conditionally renders messages based on winning, losing, or ongoing play.

Note: This is a simplified learning project. Future iterations can explore additional features like timers, sound effects, and persistent game data.

### Contributing

Feel free to fork the repository and contribute\! You can add a timer, sound effects, a high score system, or even experiment with different dice mechanics.

