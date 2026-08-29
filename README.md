# AI---internship
# Simple Rule-Based Chatbot 🤖

A beginner-friendly chatbot built in Python during my Machine Learning Internship at **Codec Technologies Pvt. Ltd.** (29 June 2026 – 29 July 2026).

The bot understands common greetings, questions and keywords typed by a user and replies automatically in real time — all without needing any heavy AI models or external APIs.

---

## 📌 Problem Statement

Most beginners find it hard to understand how conversational AI works under the hood. This project builds a simple chatbot that can understand basic user messages and reply automatically, using lightweight, easy-to-explain logic instead of complex machine learning models.

## 🎯 Objectives

- Build a simple, rule-based chatbot using Python
- Understand common greetings, questions and keywords
- Generate relevant automatic replies in real time
- Learn the basic building blocks of NLP and conversational AI
- Deliver a working, demo-ready beginner project

## 🛠️ Tools & Technologies

| Tool | Purpose |
|------|---------|
| Python | Core programming language |
| Keyword / rule-based matching | Simple if-else logic to understand input |
| Basic string handling | Lowercasing & cleaning text (beginner NLP) |
| VS Code / Jupyter Notebook | Development environment |
| Command line interface | Where the chatbot runs and chats |

## ⚙️ How It Works

1. **Collect sample inputs** – common greetings, questions, thank-yous, goodbyes
2. **Clean the text** – lowercase + remove extra spaces/punctuation
3. **Match keywords** – check cleaned input against predefined keyword lists
4. **Pick a response** – choose a suitable reply from a small response set
5. **Chat in a loop** – keep chatting until the user types `bye`

## 💬 Sample Conversation

```
You: Hi there!
Bot: Hello! How can I help you today?

You: What is your name?
Bot: I'm a simple chatbot built by Mayank.

You: Thank you
Bot: You're welcome! Happy to help.

You: Bye
Bot: Goodbye! Have a great day.
```

No external libraries are required — just Python 3.

## ✨ Features

- Understands greetings & basic questions
- Instant, automated text replies
- Runs continuously until the user says "bye"
- Lightweight — no heavy libraries needed
- Easy to extend with more keywords later

## 🔮 Future Scope

- Add more keywords and response categories
- Use NLP libraries like NLTK for better text understanding
- Add similarity-based matching (e.g. TF-IDF) instead of exact keyword matching
- Build a simple GUI or web interface
- Connect to a small knowledge base for more specific answers

## 🎓 About the Internship

This project was built as part of a 1-month, AICTE & ICAC approved Machine Learning internship at **Codec Technologies Pvt. Ltd.**, conducted in hybrid mode under the National Internship Portal.

## 👤 Author

**Mayank Kumar**
Machine Learning Intern @ Codec Technologies Pvt. Ltd.
