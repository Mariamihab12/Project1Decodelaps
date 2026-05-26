# Project1Decodelaps
# Simple Rule-Based Chatbot

## Overview
This project is a simple rule-based chatbot developed using Python.  
The chatbot interacts with users through predefined responses based on user input.

The project demonstrates basic concepts of:
- Python programming
- Conditional statements
- Loops
- User interaction
- Rule-based conversational AI

## Features
- Responds to greetings
- Answers basic questions
- Provides help instructions
- Exits conversation using commands like:
  - bye
  - exit
  - quit



## Technologies Used
- Python 3



## How It Works
The chatbot continuously takes input from the user and checks it against predefined rules using `if-elif` conditions.

Example:
- If the user types `hi`
  → Chatbot responds with a greeting.
- If the user types `what is your name`
  → Chatbot introduces itself.

## Code Example

```python
if user_input in ["hi", "hello", "hey"]:
    print("ChatBot: Hello! How can I help you?")
