# 🤖 AutoAgent — Autonomous Research Assistant

An AI agent that autonomously searches the web, reads sources, and emails you a professional research report.

## What it does
- 🔍 Searches the web for any topic you give it
- 📖 Reads and scrapes multiple sources autonomously
- 🧠 Uses AI to synthesize findings into a structured report
- 📧 Emails the report directly to any inbox

## Tech Stack
- Python
- Streamlit
- Groq API (Llama 3.1)
- BeautifulSoup4
- smtplib (Gmail SMTP)

## How to run
1. Clone the repo
2. Run `pip install streamlit groq requests beautifulsoup4 python-dotenv`
3. Add your keys to a `.env` file
4. Run `streamlit run app.py`
