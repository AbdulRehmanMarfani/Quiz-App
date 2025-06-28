
---

# Quiz App 🧠

A Python-based GUI quiz application that fetches **True/False trivia questions** from the Open Trivia Database and challenges the user with real-time score tracking and visual feedback.

---

## Features ✨

* **Live Question Fetching**: Uses Open Trivia DB API for dynamic questions.
* **Clean User Interface**: Built with `tkinter`, includes buttons with custom images.
* **Score Tracker**: Displays current score throughout the quiz.
* **Visual Feedback**: Green/red background highlights for correct/incorrect answers.
* **End-of-Quiz Summary**: Final score shown after all questions are answered.

---

## Requirements 🛠️

* Python 3.6+
* `requests` module (`pip install requests`)
* `tkinter` (comes pre-installed with most Python distributions)
* Two PNG files: `true.png` and `false.png` inside an `images/` folder

---

## File Structure 📂

```
quiz-app/
│
├── main.py             # App entry point
├── ui.py               # Handles GUI layout and button interactions
├── quiz_brain.py       # Controls quiz logic and question flow
├── data.py             # Fetches trivia questions from API
├── question_model.py   # Defines the Question class structure
└── images/
    ├── true.png        # Image for the 'True' button
    └── false.png       # Image for the 'False' button
```

---

## How to Run 🚀

1. **Clone the repository or download the source code**.

2. Make sure `requests` is installed:

   ```bash
   pip install requests
   ```

3. Place the `true.png` and `false.png` files inside the `images/` folder.

4. Run the app:

   ```bash
   python main.py
   ```

---

## Future Enhancements 🔮

* Add category and difficulty selection
* Add a timer per question
* Add high-score saving using file or database
* Add a restart button at the end of the quiz

---

## Developer Note 💡

> This project helped me strengthen my skills in:
>
> * Object-oriented programming in Python
> * Building responsive GUI apps with `tkinter`
> * Consuming and parsing REST APIs
> * Structuring clean, modular code across multiple files

---

## Credits 🙌

* **Developer**: Abdul Rehman Marfani
* **Trivia API**: [Open Trivia Database](https://opentdb.com/)
* **Images**: Replace with your own or use free icons from [Flaticon](https://www.flaticon.com/)

---

