# React Quiz App

A simple quiz application built with React. The app presents multiple-choice questions to the user, tracks the score, and displays the final result at the end of the quiz.

## Features

- Displays questions one at a time with multiple answer options.
- Tracks the user's score based on correct answers.
- Shows the total score at the end of the quiz.

## Demo

### Start Page
When the app is opened, the user sees the first question of the quiz along with four answer options as buttons.

![Start Page](./demo/start.png)

### Final Page
After all questions are answered, the app displays the total score in a message like:
> "You scored 3 out of 4."

![Final Page](./demo/final.png)

## Structure

- **App Component**: Manages the main functionality of the quiz, including:
  - Displaying questions.
  - Handling answer selection.
  - Showing the score when the quiz ends.

## How It Works

1. The application presents one question at a time.
2. Users can select an answer by clicking on the respective button.
3. The app checks if the selected answer is correct and increments the score if applicable.
4. After all questions are answered, the app displays the total score.

## Technologies Used

- **React**: Core library for building the user interface.
- **JavaScript**: Logic for managing states and rendering components dynamically.
- **CSS**: For styling the app layout and components.

## File Overview

- `App.js`: Contains the main logic for the quiz application, including state management and rendering of questions/answers.
- `questions` (within the code): A static array that holds the questions, answer options, and the correct answers.

## Usage

- Start the app to see the first question.
- Click on an answer to proceed to the next question.
- The final score will be displayed after the last question.

## Contribution

Contributions are welcome! If you'd like to contribute:

1. Fork this repository.
2. Create a new branch for your feature or bug fix.
3. Commit your changes.
4. Push your branch.
5. Open a pull request detailing your changes.

---

**Happy Learning!**
  
