# Survey Feedback Analyzer 📝

## 📌 Project Overview
The **Survey Feedback Analyzer** is a Python project that analyzes customer survey feedback using basic Python programming concepts. It collects feedback, cleans text data, counts important words, and generates useful insights from customer ratings and comments.

## 🎯 Objectives
- Store feedback using a dictionary of lists.
- Collect additional feedback from users.
- Clean textual feedback by removing punctuation, extra spaces, and uppercase letters.
- Count feedback entries containing specific words.
- Calculate the average rating.
- Identify the feedback with the longest comment.
- Extract unique words from all feedback entries.
- Sort feedback based on ratings.

## 🛠️ Technologies Used
- **Programming Language:** Python
- **Concepts:** Dictionaries, Lists, Loops, Conditional Statements, Functions, String Methods, Sets, `zip()`, and `sorted()`

## 📂 Project Features

### 1. Preloaded Feedback Data
Starts with 10 sample feedback entries containing serial numbers, names, comments, and ratings.

### 2. Add More Feedback
Allows users to enter additional feedback, including:
- Name
- Written feedback
- Rating (1–5)

Serial numbers are generated automatically.

### 3. Text Cleaning
Cleans feedback by:
- Removing punctuation (`.`, `,`, `!`, `?`)
- Removing leading and trailing spaces
- Replacing multiple spaces with a single space
- Converting text to lowercase

### 4. Word Count Insights
Counts how many feedback entries contain specific words:
- `good`
- `poor`
- `excellent`

### 5. Final Summary and Insights
- Displays the cleaned feedback dataset.
- Calculates the average rating.
- Finds the longest feedback comment by word count.
- Displays unique words without duplicates.
- Sorts feedback from highest to lowest rating.

## ▶️ How to Run the Project

1. Clone or download this repository.
2. Open the project in VS Code, PyCharm, Jupyter Notebook,google colab or another Python environment.
3. Run the Python file:

   ```bash
   python survey_feedback_analyzer.py
   ```

4. Enter the number of additional feedback entries.
5. Provide the requested names, comments, and ratings.
6. Review the generated insights.

## 📊 Expected Output
The program displays:
- Final cleaned feedback data
- Number of feedback entries containing `good`, `poor`, and `excellent`
- Average customer rating
- Longest feedback comment
- List of unique words
- Feedback sorted by rating

## 💡 Learning Outcomes
This project helped me practice Python fundamentals and understand how text cleaning, loops, functions, and data structures can be used to analyze survey feedback.

## 👩‍💻 Author
**Y. Ramyakrishna**

## 📄 License
This project is available for educational and learning purposes.
