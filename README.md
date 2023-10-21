# React Feedback App

This is a simple React application for collecting and displaying feedback
statistics. https://mikel538.github.io/goit-react-hw-04-feedback/

## Prerequisites

- Node.js and npm should be installed on your machine.

## Installation

1. Clone the repository to your local machine: git clone
   https://github.com/MikeL538/goit-react-hw-04-feedback.git

2. Change into the project directory: cd react-feedback-app

3. Install the required dependencies: npm install

4. Start the development server: npm start

5. Open your browser and go to "http://localhost:3000" to view the app.

## Components

### App (App.js)

The main component of the application that renders the feedback form and
displays statistics.

### Statistics (Statistics.jsx)

A component responsible for displaying feedback statistics. It takes the
following props:

- `good`: The number of positive feedback.
- `neutral`: The number of neutral feedback.
- `bad`: The number of negative feedback.
- `total`: The total number of feedback entries.
- `positivePercentage`: The percentage of positive feedback.

### Section (section.jsx)

A generic component for rendering a titled section. It takes the following
props:

- `title`: The title of the section.
- `children`: The content of the section.

### FeedbackOptions (feedback.jsx)

A component for rendering feedback buttons. It takes the following props:

- `options`: An array of feedback options (e.g., 'Good', 'Neutral', 'Bad').
- `onLeaveFeedback`: A function to handle user feedback selection.
