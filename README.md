# AI Code Reviewer

An AI-powered Python code review tool built with **Streamlit** and **Google Gemini 1.5 Flash API**. Paste any Python code, click Review, and instantly get feedback on bugs, syntax errors, logical flaws, and best practices.

---

## Features

- Identifies bugs, syntax errors, and logical flaws
- Provides corrected code snippets with explanations
- Focuses on accuracy, efficiency, and best coding practices
- Simple, clean Streamlit web interface
- Powered by Google Gemini 1.5 Flash

---

## Tech Stack

- Python
- Streamlit
- Google Gemini API (`google-generativeai`)

---

## How to Run

**1. Clone the repo**
```bash
git clone https://github.com/172005-dot/AI-Code.git
cd AI-Code
```

**2. Install dependencies**
```bash
pip install streamlit google-generativeai
```

**3. Add your Gemini API key**

Get a free key from [Google AI Studio](https://aistudio.google.com/app/apikey).

Open `doc.py` and replace the API key on line 4:
```python
genai.configure(api_key="YOUR_GEMINI_API_KEY_HERE")
```

**4. Run the app**
```bash
streamlit run doc.py
```

---

## How It Works

1. Enter your Python code in the text area
2. Click **Review Code**
3. Gemini 1.5 Flash analyses your code using a detailed system prompt
4. Returns identified issues, fixes, and improvement suggestions

---

## Project Structure

```
AI-Code/
│
├── doc.py        # Main Streamlit application
└── README.md
```
