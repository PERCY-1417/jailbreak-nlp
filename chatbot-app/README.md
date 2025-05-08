# Gandalf Jailbreak Chatbot UI

This is a whimsical, interactive chatbot UI built with Streamlit and Langchain, inspired by the Gandalf Lakera AI challenge. The chatbot acts as a magical gatekeeper, challenging users to unlock secret passwords across multiple levels. The UI is designed for fun, security research, and prompt engineering experiments.

## Features

- 🧙‍♂️ Gandalf character with playful and magical responses.
- Five progressive levels, each protected by a secret password.
- Jailbreak detection tool integration.
- Only Gandalf's latest response is shown—no chat history is displayed.
- User prompt and password input are visually separated for clarity.
- Whimsical, themed interface with custom styling and feedback.

## How It Works

- **Chat with Gandalf:** Enter your prompt in the "Cast your spell" area. Gandalf will respond in character.
- **Password Challenge:** If you convince Gandalf (i.e., the jailbreak tool returns "benign"), he will reveal the password for the current level.
- **Level Up:** Enter the password in the input at the bottom and proceed to the next level if correct.
- **Completion:** Successfully unlock all levels to win Gandalf's respect!

## Usage

1. Make sure you have set your `OPENAI_API_KEY` in your environment.
2. Run the app from this directory:
   ```
   streamlit run chatbot_app.py
   ```
3. Open your browser to [http://localhost:8501](http://localhost:8501) to interact with Gandalf.

## Customization

- **Passwords:** Edit `passwords.txt` to set your own level passwords (one per line).
- **Jailbreak Detection:** Replace the logic in `jailbreak_detector()` with your own tool or model.

---

This UI is part of a larger jailbreak-nlp project. For core logic and additional tools, see the main project directory.