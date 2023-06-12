

# MCQute - Multiple-Choice Quiz Application

MCQute is a simple application built using PyQt5 that allows users to take a multiple-choice quiz. The application reads questions from a CSV file or URL, presents them to the user, checks their answers, and provides hints if needed.

## Installation

1. Clone the repository:
   ```shell
   git clone https://github.com/Eratosteme/MCQute_App.git
   ```

2. Install the required dependencies. Ensure you have Python 3 and pip installed, then run:
   ```shell
   pip install -r requirements.txt
   ```

## Usage

To run the application, execute the following command in the terminal:

```shell
python mcqute.py
```

Once the application is running, follow these steps:

1. Enter the path to the question file or provide a URL to a CSV file containing the quiz questions.

2. Click the "OK" button to load the questions.

3. Answer each question as it appears, selecting the appropriate options or entering text.

4. Click the "OK" button after answering each question to check your answer.

5. If your answer is incorrect, a hint will be displayed. Use the hint to improve your answer and try again.

6. After answering all the questions, the application will display a "Congrats, you nailed it!" message.

## File Format

The quiz questions are stored in a CSV file with the following format:

```
Type,Question,Answers,Correct Answer,Hint
radio,What is the capital of France?,Paris;London;Berlin;Madrid,Paris,It's known as the City of Love.
text,Enter your name,,John Doe,Your name should be in the format "First Name Last Name."
checkbox,Which fruits are red?,Apple;Banana;Strawberry;Grapes,Apple;Strawberry,Eat them fresh or make juice!
```

- **Type**: The question type. Supported types are `radio`, `text`, and `checkbox`.
- **Question**: The text of the question.
- **Answers**: The possible answers for the question, separated by semicolons (;).
- **Correct Answer**: The correct answer(s) for the question. For multiple-choice questions, separate multiple correct answers with semicolons.
- **Hint**: A hint to help the user answer the question correctly.

Make sure your question file follows this format to ensure proper functionality of the application.

## Contributing

Contributions are welcome! If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the unlicence
