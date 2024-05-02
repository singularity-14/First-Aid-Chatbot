# Simple First Aid Chatbot

## Overview

This project implements a simple chatbot designed to provide first aid advice based on user input. The chatbot analyzes user queries and responds with relevant first aid information extracted from predefined intents.

## Dataset

- The dataset used for training the chatbot is stored in a JSON file named `intents.json`.
- The dataset contains intents, patterns, and corresponding responses for different user queries related to first aid scenarios.

## Implementation

- The chatbot is implemented in Python using the Pandas library to read and preprocess the dataset.
- It utilizes basic natural language processing techniques to match user input with predefined patterns and responses.
- The core functionality is encapsulated within the `chatbot` function, which analyzes user input and returns an appropriate response.

## Functionality

- The chatbot prompts the user to describe their situation and offers assistance based on predefined patterns.
- Users can input their queries, and the chatbot provides relevant first aid advice or information.
- The chatbot allows users to exit or quit the conversation by typing "exit" or "quit".

## Usage

1. **Data Preparation**:
   - Ensure the `intents.json` file is available and contains the necessary intents, patterns, and responses for first aid scenarios.

2. **Chatbot Execution**:
   - Run the provided Python script to start the chatbot.
   - Follow the prompts to input your query and receive first aid advice.

3. **Interaction**:
   - Interact with the chatbot by describing your situation or asking for first aid advice.
   - Type "exit" or "quit" to end the conversation and exit the chatbot.

## Dependencies

- Python 3.x
- Pandas
- NumPy
- JSON

## License

This project is licensed under the [MIT License](LICENSE).

## Author

- Rachit
