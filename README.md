Library and Information Science Quiz Application
This is a simple, interactive web-based quiz application for Library and Information Science, designed to help users test their knowledge. The application features a timed quiz, immediate feedback on answers, and a comprehensive review summary at the end.

Features
50 Multiple-Choice Questions: Based on the provided Library and Information Science PDF.

2-Hour Timer: A countdown timer is displayed, and the quiz automatically submits when time runs out.

Interactive Question Navigation: Users can move between questions using "Previous" and "Next" buttons.

Answer Checking: Users can check their answer for each question to see if it's correct or incorrect, with the correct answer highlighted.

Score Summary: At the end of the quiz, a summary displays the total questions, correct answers, incorrect answers, and unanswered questions.

Answer Review: A "Review Answers" button allows users to go through all questions, see their selected answers, and identify the correct answers for incorrect or unanswered questions.

Responsive Design: The application is designed to be usable on various devices, including mobile phones and PCs.

Hindi Questions: Quiz questions and options are presented in Hindi.

English UI: Navigation buttons and other user interface elements are in English.

How to Use
Open the Application: Simply open the index.html file in any modern web browser (Google Chrome, Mozilla Firefox, Microsoft Edge, Safari, etc.).

Start the Quiz: The quiz will begin automatically, and the timer will start counting down.

Navigate Questions: Use the "Previous Question" and "Next Question" buttons to move between questions.

Select an Answer: Choose one of the options for each question.

Check Answer (Optional): Click the "Check Answer" button to see if your selected answer is correct. The correct option will be highlighted in green, and your incorrect selection (if any) in red.

Finish Quiz: Once you reach the last question, click the "Finish Quiz" button to submit your answers and view your score.

Review Answers: After finishing, click the "Review Answers" button to see a detailed breakdown of all questions, your responses, and the correct answers.

Setup and Hosting
This application is a static website, meaning it consists only of HTML, CSS, and JavaScript files. It does not require a backend server or database.

Local Setup
To run the quiz locally on your computer:

Download the Code:

Copy the entire HTML code provided in the interactive_quiz_app Canvas.

Paste it into a new text file.

Save the file as index.html.

Open in Browser: Double-click the index.html file. It will open in your default web browser.

Hosting Online
To make your quiz accessible to others via a web link, you can host it using platforms like GitHub Pages or Netlify.

GitHub Pages
Create index.html: Save your quiz code as index.html.

Create a GitHub Repository: Sign up for GitHub (if you haven't already) and create a new public repository (e.g., my-quiz-app).

Upload index.html: Upload your index.html file directly to the root of this new repository.

Enable GitHub Pages: Go to your repository's Settings > Pages. Under "Build and deployment," select "Deploy from a branch" and choose the main (or master) branch. Click "Save."

Access Your Site: Your quiz will be live at https://your-username.github.io/your-repository-name/ within a few minutes.

Netlify
Ensure GitHub Repository: Make sure your index.html is already in a GitHub repository (refer to GitHub Pages steps 1-3).

Sign Up/Log In to Netlify: Go to netlify.com and sign up or log in, preferably with your GitHub account.

Import Project: Click "Add new site" -> "Import an existing project" -> "Deploy with GitHub."

Select Repository: Choose the GitHub repository containing your index.html.

Deploy: Netlify will automatically detect the settings. Click "Deploy site."

Access Your Site: Netlify will provide a unique URL (e.g., https://random-name-12345.netlify.app/) where your quiz will be live.

Important Note for Correct Answers
The correctAnswerIndex values in the quizQuestions JavaScript array are currently placeholders. To enable accurate answer checking and scoring, you must manually update these values in the index.html file with the correct 0-indexed option for each question.

Technologies Used
HTML5: For the structure of the quiz.

CSS3 (Tailwind CSS): For styling and responsive design.

JavaScript: For quiz logic, timer, and interactivity.

Feel free to reach out if you have any questions!
