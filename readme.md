# Introduction to Python Programming — Course README

Welcome to the **Introduction to Python Programming** course! 🎉

This course will introduce you to the fundamentals of Python programming through hands-on exercises, Jupyter notebooks, and small projects. Whether you're new to coding or looking to strengthen your foundations, this course will guide you step-by-step toward becoming confident in writing and understanding Python code.

---

## 🧭 Course Overview

**Duration:** 10–12 Weeks (Flexible — approx. 30–45 total hours)
**Format:** Lectures + Hands-on Labs using Jupyter Notebooks
**Prerequisites:** None (basic computer literacy recommended)

You will:

* Learn the basic syntax and structure of Python.
* Develop problem-solving and logical thinking skills.
* Write, test, and debug Python programs.
* Work with variables, loops, functions, and data structures.
* Explore basic file handling and data analysis using libraries like `pandas` and `matplotlib`.
* Build simple projects by the end of the course.

---

## 🛠️ Getting Started

### 1. Clone or download this repository

```bash
git clone https://github.com/crisjamir/PythonForKids
cd PythonForKids
```

If you don’t use Git, you can click **Code → Download ZIP**, extract it, and open it in VS Code.

### 2. Set up your environment

Follow the detailed setup instructions in:

📘 **[VS Code + Jupyter Setup Guide](./VS%20Code%20+%20Jupyter%20Setup%20for%20Intro%20to%20Python%20Course.md)**

That guide walks you through:

* Installing Python and VS Code
* Creating a virtual environment
* Installing required libraries via `requirements.txt`
* Running Jupyter Notebooks directly inside VS Code

### 3. Install course dependencies

Once your virtual environment is active:

```bash
pip install -r requirements.txt
```

### 4. Launch Jupyter Notebook in VS Code

* Open a notebook file under `/notebooks` (e.g., `01-setup.ipynb`).
* Select the correct interpreter (the `.venv` environment).
* Run the cells to verify your setup.

---

## 📂 Repository Structure

```
intro-to-python/
├─ notebooks/         # Jupyter notebooks for weekly lessons and labs
├─ src/               # Optional Python scripts
├─ data/              # Sample data files for exercises
├─ requirements.txt   # Python dependencies
├─ README.md          # Course overview (this file)
└─ VS Code + Jupyter Setup for Intro to Python Course.md
```

---

## 📘 Weekly Topics

| Week | Topic                       | Focus                                  |
| ---- | --------------------------- | -------------------------------------- |
| 1    | Introduction to Programming | Python setup, syntax, print/input      |
| 2    | Variables and Data Types    | Strings, numbers, casting              |
| 3    | Control Flow                | If-else, logical operators             |
| 4    | Loops                       | For, while, range                      |
| 5    | Functions                   | Modular programming, parameters, scope |
| 6    | Data Structures             | Lists, tuples, sets, dictionaries      |
| 7    | Strings & Files             | String methods, file handling          |
| 8    | Error Handling              | Try/except, debugging basics           |
| 9    | Modules & Libraries         | Using built-in and external modules    |
| 10   | Final Project               | Integrate concepts into a small app    |

---

## 🧩 Example Projects

At the end of the course, you’ll develop a small project to demonstrate your learning. Example ideas include:

* **Expense Tracker:** Manage simple budgets using file I/O.
* **Quiz App:** Interactive quiz using functions and conditionals.
* **Data Analyzer:** Load and summarize data from a CSV.
* **File Organizer:** Automate file sorting in folders.

---

## 🧪 Testing Your Code

You can write simple unit tests for your Python scripts using `pytest` (already in `requirements.txt`).

Example test command:

```bash
pytest -v
```

---

## 🧰 Tools Used

* [Python 3.x](https://www.python.org/)
* [Visual Studio Code](https://code.visualstudio.com/)
* [Jupyter Notebooks](https://jupyter.org/)
* Libraries: `numpy`, `pandas`, `matplotlib`, `seaborn`, `requests`, `openpyxl`

---

## 🙌 Contributing

If you’d like to contribute by improving materials or exercises:

1. Fork this repo.
2. Create a new branch (`feature/improve-lab-02`).
3. Submit a pull request with a short explanation.

---

## 📄 License

This course content is provided under the **MIT License**. You may freely use and adapt it for educational purposes with proper attribution.

---

## 💬 Support

For setup help or troubleshooting:

* Check the [Setup Guide](./VS%20Code%20+%20Jupyter%20Setup%20for%20Intro%20to%20Python%20Course.md)
* Contact your instructor or teaching assistant

Happy coding! 🐍✨
