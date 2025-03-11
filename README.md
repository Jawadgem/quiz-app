# Quiz Application

## Overview
This is a simple quiz application built using **Streamlit**. The app randomly selects questions from a predefined list and allows users to answer them. It provides immediate feedback on whether the answer is correct or incorrect before moving to the next question.

## Features
- Randomized questions from a predefined list
- Multiple-choice answer selection
- Immediate feedback on correct and incorrect answers
- Automatic transition to the next question after a delay
- User-friendly web interface with **Streamlit**

## Requirements
To run this application, you need to have the following installed:

- Python 3.x
- Streamlit

## Installation
1. Clone this repository or create a new project folder and navigate to it:
   ```sh
   git clone https://github.com/your-repo/quiz-app.git
   cd quiz-app
   ```
2. Install the required dependencies:
   ```sh
   pip install streamlit
   ```

## Running the Application
To start the quiz application, run the following command in your terminal:
```sh
streamlit run app.py
```

## How It Works
1. A random question is displayed with multiple-choice answers.
2. The user selects an answer and clicks the **Submit Answer** button.
3. The app checks the answer and provides feedback (✅ Correct or ❌ Incorrect).
4. After a short delay, a new random question is displayed.

## Code Structure
- **`questions`**: A list of dictionaries containing quiz questions, options, and correct answers.
- **Session State**: Used to maintain the current question across interactions.
- **Streamlit Widgets**:
  - `st.title()` for the app title
  - `st.subheader()` for displaying the question
  - `st.radio()` for answer selection
  - `st.button()` for submitting the answer
  - `st.success()` and `st.error()` for displaying feedback
- **Randomization**: Ensures each question is randomly selected to keep the quiz engaging.

## Future Enhancements
- Add a scoring system
- Implement a timer for each question
- Include more diverse question categories
- Allow users to upload custom quiz questions

## License
This project is open-source and free to use.

## Author
Developed by Jawad Nasir

