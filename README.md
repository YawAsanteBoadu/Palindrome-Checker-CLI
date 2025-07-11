# Palindrome-Checker-CLI
# Palindrome Checker CLI

A simple and robust command-line interface (CLI) application built with vanilla Python to determine if a given word or phrase is a palindrome. This project is specifically designed as a hands-on exercise to practice core Python function logic, emphasizing **separation of concerns** and the **Don't Repeat Yourself (DRY)** principle.

---

## 🌟 Features

* **Palindrome Detection:** Accurately identifies whether an input string reads the same forwards and backward.
* **Case-Insensitive Check:** Handles input without regard to capitalization (e.g., "Racecar" is treated as a palindrome).
* **Whitespace & Punctuation Ignored:** Cleans the input string to focus purely on alphanumeric characters for the check (e.g., "Madam, I'm Adam" is correctly identified).
* **User-Friendly Interface:** Provides clear prompts and results directly in the terminal.
* **Pure Python:** Developed using only standard Python libraries, focusing on fundamental language constructs and algorithms.

---

## 🚀 Technologies Used

* **Python 3.x:** The core programming language.

---

## ⚙️ How to Install & Run

1.  **Clone the repository:**
    ```bash
    git clone [https://github.com/YourGitHubUsername/Palindrome-Checker-CLI.git](https://github.com/YourGitHubUsername/Palindrome-Checker-CLI.git)
    cd Palindrome-Checker-CLI
    ```
    *(Remember to replace `YourGitHubUsername` and `Palindrome-Checker-CLI` with your actual GitHub username and repository name.)*

2.  **Run the application:**
    Open your terminal or command prompt, navigate to the project directory, and execute the main script:
    ```bash
    python main.py # Or whatever your main script file is named (e.g., app.py)
    ```

---

## 💡 How to Use

Once the application is running, you will be prompted to enter a word or phrase:

Enter a word or phrase to check if it's a palindrome:

Type your input and press Enter. The application will then output whether your input is a palindrome or not.

**Examples:**
* `racecar` -> Is a palindrome!
* `Madam, I'm Adam` -> Is a palindrome!
* `hello` -> Is not a palindrome.

---

## 📘 Learning Focus: Clean Code Principles

This project serves as a dedicated practice ground for fundamental software design principles:

* **Separation of Concerns:** Logic for input handling, string cleaning, and the actual palindrome check are implemented in distinct functions. This makes the code easier to read, test, and maintain.
* **Don't Repeat Yourself (DRY):** Common logic (e.g., string normalization) is encapsulated in reusable functions to avoid code duplication and promote efficiency.
* **Function-Oriented Programming:** Emphasis is placed on creating well-defined, single-purpose functions for clarity and modularity.

---

## ✍️ Author

* **[YawAsanteBoadu]** - [Link to my GitHub Profile](https://github.com/Yawasanteboadu)

---
