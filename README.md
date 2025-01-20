My quiz_app works in 5 stages as:

1.Initialization:
  The app starts at the WelcomeScreen.
  QuizModel is created and used to fetch questions from the API.

2.Starting the Quiz:
  The user taps the "Start Quiz" button.
  The app navigates to the QuizScreen.
  
3.Taking the Quiz:
  The QuizScreen displays the first question and starts the timer.
  The user selects an option.
  QuizModel checks the answer, updates the score, and moves to the next question.
  The timer resets.
  
4.Completing the Quiz:
  When all questions are answered or the timer expires for all questions:
  The app navigates to the SummaryScreen.

5.Viewing Summary:
The SummaryScreen displays the quiz results, showing each question, the correct answer, and the user's answer.
