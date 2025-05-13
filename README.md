<h1 align="center">J.A.R.V.I.S - Chatbot Project</h1>
<p align="center">
<p align="center">
  <img src="https://github.com/user-attachments/assets/e124f981-e926-487c-aebb-f1231a18faeb" width="300">
</p>

## Overview
J.A.R.V.I.S!
 is a chatbot built using **Natural Language Toolkit (NLTK)** in Python. The chatbot is designed to engage in basic conversations with users by recognizing patterns in their input and providing contextually appropriate responses. J.A.R.V.I.S can assist with a variety of queries, including greetings, weather-related questions, fun facts, and more.

## Features
* **Pattern Matching**: J.A.R.V.I.S uses regular expressions to match user inputs and respond with predefined answers.
* **Fun Facts**: J.A.R.V.I.S can share interesting facts when asked.
* **Interactive Chat**: Responds to various inputs, such as greetings and questions about itself.
* **Extensibility**: You can easily add new patterns and responses to customize the chatbot.
* **Simple Math**: J.A.R.V.I.S can perform basic math calculations.

## Technology Stack
* **Python**: The primary programming language used for the chatbot.
* **NLTK (Natural Language Toolkit)**: Used for text processing and implementing pattern matching.
* **Regular Expressions**: Utilized for recognizing and responding to user input patterns.

## Setup Instructions

### Prerequisites
Before running J.A.R.V.I.S, ensure that Python 3.6+ is installed on your machine.

1. **Install Python**: If you don't have Python installed, download it from [here](https://www.python.org/downloads/).
2. **Install NLTK**: The chatbot requires the `nltk` library for processing natural language.

### Installing Dependencies
1. Clone the repository:
```bash
git clone https://github.com/Jmveasy14/ChatBot-Project.git
cd ChatBot-Project
```

2. Install the required Python packages:
```bash
pip install nltk
```

3. **Download NLTK Data**: Open a Python terminal and run the following commands:
```python
import nltk
nltk.download('punkt')
```

## Usage
1. Open the `chatbot.ipynb` file in **Jupyter Notebook** or any Python IDE you prefer.
2. Run the cells to initialize J.A.R.V.I.S and start chatting.
3. Type your queries or greetings, and J.A.R.V.I.S will respond based on predefined patterns.

## Example Interactions
* **User**: "hello"
* **J.A.R.V.I.S**: "Hey there!"
* **User**: "tell me a fun fact"
* **J.A.R.V.I.S**: "Did you know that honey never spoils? Archaeologists have found pots of honey in ancient tombs that are over 3,000 years old!"
* **User**: "how is the weather in Tokyo?"
* **J.A.R.V.I.S**: "The weather in Tokyo is amazing as always!"
* **User**: "what's 2 + 2?"
* **J.A.R.V.I.S**: "2 + 2 is 4. Simple math!"

## Contributing
Feel free to fork this repository and contribute by adding new features, responses, or improving functionality.

### How to Contribute:
1. Fork the repository.
2. Create a new branch (`git checkout -b feature-name`).
3. Make your changes and commit (`git commit -am 'Add new feature'`).
4. Push the changes (`git push origin feature-name`).
5. Submit a pull request.

## License
This project is open-source and available under the MIT License. See the LICENSE file for more details.

## Contact
* **Joshua Veasy**: [GitHub](https://github.com/Jmveasy14)
* **Email**: jmveasy14@gmail.com
