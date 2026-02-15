# Medical Chatbot with Memory

This is a simple medical chatbot that uses LangChain and HuggingFace models to provide medical information with conversation memory capabilities.

## Setup

1. Make sure you have Python installed on your system
2. Install the required packages:
   ```
   pip install langchain langchain_community langchain_huggingface faiss-cpu
   ```
3. Get a HuggingFace API token:
   - Create an account on [HuggingFace](https://huggingface.co/)
   - Go to your profile settings and create an API token
   - Copy the token and replace `"your_huggingface_token_here"` in the `memory_chat_bot.py` file

## Usage

Run the chatbot with:

```
python memory_chat_bot.py
```

Interact with the chatbot by typing your medical questions. The chatbot will remember your conversation history and provide contextually relevant responses.

Type `exit` to end the conversation.

## Features

- Conversation memory that maintains context throughout the interaction
- Medical-focused prompt template
- Uses HuggingFace's language models for generating responses
- Simple command-line interface


## Disclaimer

This chatbot is for informational purposes only and is not a substitute for professional medical advice, diagnosis, or treatment. Always consult with a qualified healthcare provider for medical concerns.
