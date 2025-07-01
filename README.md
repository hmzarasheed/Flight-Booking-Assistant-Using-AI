# FlightAI Assistant ✈️

FlightAI Assistant is an interactive airline chatbot that uses OpenAI's GPT models with tool/function calling to answer user queries such as flight ticket pricing. It provides fast, courteous, and accurate answers in a web-based Gradio chat interface.

---

## 🧠 Features

- Conversational assistant built with OpenAI's `gpt-4o-mini`.
- Responds to airline-related customer questions.
- Calls a backend function (`get_ticket_price`) when users ask for ticket prices.
- Returns polite, short answers per the system instructions.
- Fully interactive through a Gradio web interface.

---

## 🧩 Tools Used

- `OpenAI` — for LLM-powered conversation and function-calling.
- `Gradio` — for building the chat interface.
- `dotenv` — for managing environment variables.
- `PIL` and `IPython.display` — imported, but **not actively used** in this version of the notebook.

---

## 🔧 Setup Instructions

1. **Install required libraries**:
   ```bash
   pip install openai gradio python-dotenv
