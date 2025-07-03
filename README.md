
# 🤖 Gemini Chatbot (Desktop App)

A modern, sleek desktop chatbot interface built with **CustomTkinter** and powered by **Google's Gemini API**. This chatbot app provides a smooth conversational experience with a user-friendly UI.

---

## ✨ Features

- 🪄 Gemini 1.5 Flash API integration
- 💬 Clean, scrollable chat interface
- 🎨 CustomTkinter-based modern UI
- 🧹 Clear Chat functionality
- ⌨️ Send messages using Enter key or button

---

## 🚀 How to Run

### 1. Clone the Repository

```bash
git clone https://github.com/your-username/gemini-chatbot-ui.git
cd gemini-chatbot-ui
```

### 2. Install Required Packages

```bash
pip install customtkinter requests
```

### 3. Run the App

```bash
python chatbot_using_gemini.py
```

---

## 🧠 Powered By

- [Google Gemini API (1.5 Flash)](https://ai.google.dev/)
- [CustomTkinter](https://github.com/TomSchimansky/CustomTkinter)

---

## 🧰 Project Structure

```
chatbot_using_gemini.py   # Main application file
```

---

## 🔐 API Key Notice

> ⚠️ **Important:** The current file uses a hardcoded Gemini API key.
>
> Replace it with your own key or load it securely using environment variables:
>
> ```python
> import os
> GEMINI_API_KEY = os.getenv("GEMINI_API_KEY")
> ```

---

## 🖼️ UI Overview

- Left sidebar with branding and Clear button
- Right pane with:
  - Title bar
  - Scrollable chat area
  - Message input + send button

---

## ✍️ Author

**Ausaf Ansari**

---

## 📝 License

This project is licensed under the MIT License.

