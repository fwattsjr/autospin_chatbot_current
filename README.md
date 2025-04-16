This repository includes a python program, chatbot.py, that implements a chabot application in Streamlit. 
The Streamlit app can be found at https://autospin-chatbot-current.streamlit.app/

The repository includes:
requirements.txt - lists the dependencies for the chatbot.py app
chatbot.py - program for the chatbot app. The app includes a system prompt for OpenAI's GPT-4o model. The chatbot stores the chat history as context for generating responses to user inputs.

Potential additions that can be explored for implementation in C4:
* Provide the chatbot knowledge of which part of the assessment task the student is currently on (e.g., the simulation task, the scaffolded claim-evidence-reasoning questions, etc.)
* Provide the chatbot with the students' input on each part of the assessment task (e.g., the data table, responses to the scaffolded claim-evidence-reasoning questions)
* Information about the evaluation and feedback provided from the feedback system on the final question of the task (from the claim-evidence-reasoning evaluation models and eventual feedback system developed by UGA)
Each of these features would provide the chatbot with additional context to inform how it responds to student inputs.
