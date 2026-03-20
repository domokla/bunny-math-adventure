# Nyuszis Matek

Nyuszis Matek is a simple, child-friendly browser math game built with plain HTML, CSS, and vanilla JavaScript.

The player helps a bunny solve short math questions. Each round contains 5 questions, and if the player gets at least 4 correct answers, they receive a random reward image from the `images/` folder.

## Features

- Single-file game in `index.html`
- Large colorful UI designed for young children
- Works on desktop and mobile
- Random one-step addition and subtraction questions
- Random names, numbers, and objects
- Occasional simple comparison questions such as "Peti ate 2 fewer chocolates than Mate"
- Immediate visual feedback after each answer
- Bunny reaction animations
- End-of-round result screen
- Random reward image for strong performance
- Restart button for a new game

## Project Structure

```text
.
├── index.html
├── images/
└── README.md
```

## How to Run

No build step or dependencies are required.

1. Open `index.html` in a web browser.
2. Start answering the questions.
3. Finish all 5 questions to see the result.

## Game Rules

- Each game round has 5 questions.
- Questions are shown one at a time.
- The player chooses from 2 to 4 answer buttons.
- A correct answer gives immediate positive feedback.
- A wrong answer gives immediate correction feedback.
- After a short delay, the next question appears.
- If the final score is `4 / 5` or better, a random reward image is shown.

## Customization

The game is easy to modify inside `index.html`.

- Update the `names` array to add or remove names.
- Update the `nameDativeForms` object to keep Hungarian name forms correct.
- Update the `items` array to change the basic story objects.
- Update `comparisonScenarios` to change the comparison-style question texts.
- Change the comparison question frequency in the `createQuestion()` function.
- Replace or add reward images inside the `images/` folder.
- Adjust colors and layout in the CSS section near the top of the file.

## Technologies

- HTML
- CSS
- Vanilla JavaScript

## Notes

- The game is intentionally simple and readable so it can be edited quickly.
- All logic, styling, and markup live in a single file for easy sharing.

## License
Images are from [Pexels](https://www.pexels.com/) and [Unsplash](https://unsplash.com/) and are free to use for personal and commercial purposes.
