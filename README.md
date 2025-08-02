# 🐍 Python Projects Collection

A curated collection of Python projects grouped by **difficulty level** — ideal for learners and developers looking to enhance their skills step-by-step.

Whether you're just starting out or diving into more advanced use cases, this repo provides practical examples and hands-on learning in Python.

---

## 📚 Project Categories

### 🟢 Beginner Level

> Focused on fundamentals, syntax, data types, loops, conditionals, and basic functions.

- **Number Guessing Game**
- **Simple Calculator (CLI)**
- **Palindrome Checker**
- **Basic Web Scraper (using `requests` + `BeautifulSoup`)**
- **Temperature Converter**

📂 Location: `./beginner/`

---

### 🟡 Intermediate Level

> Involves working with files, APIs, basic OOP, external libraries, error handling, and simple automation.

- **Weather CLI using OpenWeather API**
- **To-Do List Manager with JSON Storage**
- **Simple Flask App**
- **Command-Line YouTube Downloader**
- **Image Converter (e.g., PNG to JPG using Pillow)**

📂 Location: `./intermediate/`

---

### 🔴 Advanced Level

> Focus on scalable apps, integrations, complex logic, multithreading, design patterns, and real-world tools.

- **REST API with FastAPI**
- **Data Processing Pipeline (Pandas + CSV)**
- **Asynchronous Web Scraper with `aiohttp`**
- **Machine Learning Pipeline (Scikit-learn)**
- **Real-Time Dashboard with Dash**

📂 Location: `./advanced/`

---

## 🛠 Requirements

Each project contains its own `requirements.txt` file. To set up a virtual environment and install dependencies:

```bash
# Create a virtual environment (optional but recommended)
python -m venv venv
source venv/bin/activate  # or venv\Scripts\activate on Windows

# Install dependencies for a specific project
cd ./intermediate/weather-cli/
pip install -r requirements.txt
