# 🦙 LLAMA 3.3 Chatbot

## Description
Welcome to the **LLAMA 3.3 Chatbot**! This is a simple chatbot interface built using **Streamlit** and powered by **Groq's API** with the **LLAMA 3.3-70B** model. 🚀

---
## Working Link
https://lamachatbot.streamlit.app/

![Screenshot 2025-04-02 094854](https://github.com/user-attachments/assets/f583f450-c0b2-4412-9a90-bbc494fef288)

## Features
- **Interactive Chat** 💬: Engage with LLAMA 3.3 via a sleek chat interface.
- **Persistent Chat History** 🔄: Retain previous messages during the session.
- **Environment Variable Management** 🔑: Securely loads API key from a `config.json` file.

## Installation

### Prerequisites
Ensure you have **Python 3.8+** installed on your system.

### Steps
1. **Clone the repository**
   ```sh
   git clone https://github.com/your-repo/llama-chatbot.git
   cd llama-chatbot
   ```
2. **Install dependencies**
   ```sh
   pip install streamlit groq
   ```
3. **Configure API Key**

- Create a config.json file in the project directory and add your Groq API Key:
  ```sh
  {
  "GROQ_API_KEY": "your_api_key_here"
  }
  ```
4. Run the Chatbot 🏃‍♂️
   ```sh
   streamlit run app.py
   ```
   ## Project Structure  
   ```sh
   📂 llama_chatbot
   ├── 📄 app.py          # Main application file
   ├── 📄 config.json     # Configuration file with API key
   └── 📄 README.md       # Project documentation (this file!)
   ```
   ##  Usage
- Open the chatbot in your browser after running the command.

- Type your message in the chat input box.

- Receive responses from the LLAMA 3.3 model.

# 🚀 Happy Chatting with LLAMA 3.3! 🦙💬
