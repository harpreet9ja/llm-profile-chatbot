# 🤖 AI Persona Chatbot

An AI-powered chatbot that answers questions about a person’s career, skills, and experience by using their resume (PDF) and summary data.

Built with OpenAI, Gradio, and Python.

---

## 🚀 Features

* Chat interface using Gradio
* Persona-based responses (acts like the profile owner)
* Reads resume from PDF
* Uses structured summary + LinkedIn data
* Context-aware conversation (chat history supported)

---

## 🛠️ Tech Stack

* Python
* OpenAI API
* Gradio
* PyPDF
* python-dotenv

---

## 📂 Project Structure

```
.
├── app.py
├── me/
│   ├── Profile.pdf
│   └── summary.txt
├── .env
├── requirements.txt
```

---

## ⚙️ Setup

### 1. Clone the repo

```
git clone https://github.com/your-username/ai-persona-chatbot.git
cd ai-persona-chatbot
```

### 2. Create virtual environment

```
python -m venv venv
source venv/bin/activate   # Mac/Linux
venv\Scripts\activate      # Windows
```

### 3. Install dependencies

```
pip install -r requirements.txt
```

### 4. Add OpenAI API key

Create a `.env` file:

```
OPENAI_API_KEY=your_api_key_here
```

---

## ▶️ Run the app

```
python app.py
```

Then open the Gradio UI in your browser.

---

## 💡 How it works

* Extracts text from a PDF resume
* Combines it with a summary file
* Uses a system prompt to simulate a real person
* Sends chat history + user message to OpenAI
* Returns contextual responses

---

## 📌 Example Use Cases

* Personal portfolio chatbot
* Resume assistant
* AI-based profile Q&A system
* Demo project for LLM apps

---

## ⚠️ Notes

* Do not commit `.env` file
* Keep API keys secure
* Large PDFs may need preprocessing

---

## 📄 License

MIT License
