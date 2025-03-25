# Getting Started with Create React App
# Interactive Quiz App



# 📝 Project Description
This is a simple quiz application where users can answer multiple-choice questions, check their answers, and track their score. The app dynamically updates questions and provides a final result at the end.



# 🔧 Functions Used 
- 1️⃣ checkAns(e, ans) :

- Checks if the selected answer is correct.
- Updates the score if the answer is correct.
- Highlights the correct or wrong answer.

- 2️⃣ next():

- Moves to the next question.
- Prevents moving forward unless an answer is selected.
- Resets the answer highlights for the new question.

- 3️⃣ reset()

- Resets the quiz to the first question.
- Resets the score and the answer selection state.



# ⚡ Hooks Used in the Project:
- 🔹 useState → Manages the quiz state, including the current question, score, and selection lock.
- 🔹 useRef → References answer options to update their styles dynamically.



### `npm start`

Runs the app in the development mode.\
Open [http://localhost:3000](http://localhost:3000) to view it in your browser.

The page will reload when you make changes.\
You may also see any lint errors in the console.

### `npm test`

Launches the test runner in the interactive watch mode.\
See the section about [running tests](https://facebook.github.io/create-react-app/docs/running-tests) for more information.

### `npm run build`

Builds the app for production to the `build` folder.\
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.\
Your app is ready to be deployed!




