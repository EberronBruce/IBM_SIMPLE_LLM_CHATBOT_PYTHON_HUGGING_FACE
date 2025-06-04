# BlenderBot Chatbot in Python

A simple chatbot using an LLM from Hugging Face, built as part of IBM’s AI Developer certification.

This project is a simple command-line chatbot built using the [Facebook BlenderBot 400M distilled model](https://huggingface.co/facebook/blenderbot-400M-distill), powered by Hugging Face's `transformers` library.

---

## Tech Stack
- Python 3.x
- Hugging Face Transformers
- IBM Cloud
- Skills Network

---

## 🧰 Features

- 🔁 Text-based conversational interface
- 🤗 Hugging Face transformer models
- 🧠 AI-driven responses powered by LLMs
- ✅ Based on an IBM lab project
- Uses the `facebook/blenderbot-400M-distill` conversational model.

---

## 🔧 Setup Instructions

1. Clone this repo:

```bash
git clone https://github.com/EberronBruce/ibm_simple_llm_chatbot_huggingface.git
cd ibm_simple_llm_chatbot_huggingface
```

Before running the chatbot, follow these steps to set up a Python virtual environment and install dependencies:

### 1. Install `virtualenv` (if not already installed)

```bash
pip3 install virtualenv
```

### 2. Create and activate a virtual environment
```bash
virtualenv my_env        # Create a virtual environment named my_env
source my_env/bin/activate  # Activate the environment (use my_env\Scripts\activate on Windows)
```

### 3. Install required Python packages
```bash
python3 -m pip install transformers==4.30.2 torch
```

### 🚀 Running the Chatbot
```bash
python3 chatbot.py
```

(Replace chatbot.py with the actual name of your script file if different.)

The bot will start an interactive loop in the terminal. You can chat with it by typing messages after the > prompt.


To stop the conversation, use Ctrl+C.

### 📦 Dependencies

- transformers==4.30.2
- torch

## 📄 License

This project is provided for educational purposes and uses models under the terms of the [Facebook BlenderBot model license](https://huggingface.co/facebook/blenderbot-400M-distill).


