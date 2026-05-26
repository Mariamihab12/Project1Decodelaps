# Project1Decodelaps
# Rule-Based & Smart NLP Chatbot Project

##  Overview

This project contains **two versions of a chatbot implemented in Python**:

1.  **Simple Rule-Based Chatbot**
2.  **Advanced Smart NLP Chatbot**

Both projects demonstrate the evolution from basic rule-based logic to a more intelligent chatbot using Natural Language Processing (NLP).

They showcase core concepts in:
- Python programming
- Conditional logic and loops
- Rule-based AI systems
- Natural Language Processing (NLP)
- Sentiment analysis
- Basic conversational memory



#  1. Simple Rule-Based Chatbot

##  Description

This is a beginner-friendly chatbot built using only Python conditionals and loops.  
It responds to user inputs using predefined rules.



##  Features

- Responds to greetings (hi, hello, hey)
- Answers basic predefined questions
- Provides simple help instructions
- Exits using commands:
  - bye
  - exit
  - quit
- Continuous user interaction using a loop



##  Technologies Used

- Python 3 (no external libraries)



##  How It Works

The chatbot reads user input and checks it using `if-elif` statements.

### Example Logic:
```python
if user_input in ["hi", "hello", "hey"]:
    print("ChatBot: Hello! How can I help you?")
