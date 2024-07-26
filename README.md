# React Quiz

**Note: This project is based on [The Ultimate React Course by Jonas Schmedtmann](https://www.udemy.com/course/the-ultimate-react-course/)**.

The React Quiz app is a demo of several React concepts that quizzes the user on some basic questions about React itself. The app itself employs the Context API and useReducer hook to manage state. The quiz features 15 questions with answers displayed for user review and a scoring system.

**Live Deployment: [https://pjf3av-react-quiz.netlify.app/](https://pjf3av-react-quiz.netlify.app/)**.

## Key Features
- **Dynamic Question Handling:** Questions and answers are loaded dynamically for each quiz session.
- **State Management with Context API and useReducer:** Organized management of quiz state, including current question, selected answers, and score.
- **Immediate Feedback:** Users receive instant feedback on their answers.
- **Score Calculation:** Displays the user's score upon completing the quiz.
- **Progress Tracking:** Users can monitor their progress throughout the quiz.
- **Restart Capability:** Option to restart the quiz at any point.

## JSON Server

The main branch of this repo relies on a live JSON server, a simulation of interaction with a backend server to provide question data. The live version (on the "netlify" branch) loads the questions directly from the JSON file in the "src" folder. 

## Getting Started
To clone and deploy this project locally, follow these simple steps.

### Prerequisites

First, make sure you have the latest version of npm:

```bash
npm install npm@latest -g
```

### Installation

1. Clone this repo

```
git clone https://github.com/pjf3av/react-quiz.git
```

2. Install NPM packages

```
npm i
```

3. Start JSON server

```
npm run server
```

4. Start server

```
npm start
```
