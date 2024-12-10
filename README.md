## Math Problem Solver and Data Search Assistant

This project is a web-based assistant built using Streamlit and LangChain. It helps users solve math problems, perform reasoning tasks, and search for information online. The assistant leverages tools like Groq Gemma 2 for reasoning and Wikipedia for information retrieval.

## Features

- **Math Problem Solver**: Solves mathematical questions with step-by-step explanations.
- **Reasoning Assistant**: Provides logical solutions to reasoning-based questions.
- **Data Search**: Retrieves information from Wikipedia and other sources.
- **Interactive UI**: Simple and intuitive interface for user interaction.

## Installation

1. Clone the repository:
   ```bash
   git clone <repository_url>
   cd <repository_directory>
   ```

2. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

3. Set up your Groq API key:
   - Enter your API key in the app's sidebar when prompted.

## Usage

1. Run the application:
   ```bash
   streamlit run app.py
   ```

2. Enter your Groq API key in the sidebar to start.

3. Use the text area to input questions, such as:
   - Math problem: "I have 5 bananas and 7 grapes. I eat 2 bananas and give away 3 grapes. How many fruits do I have?"
   - Reasoning question: "If all cats are mammals and some mammals are dogs, can a cat be a dog?"

4. Click the "Find my answer" button to get a detailed response.

## Requirements

- Python 3.8+
- Key Python Libraries:
  - `langchain`
  - `streamlit`
  - `openai`
  - `pandas`
  - and others listed in `requirements.txt`

## Tools and Technologies

- **LangChain**: For building the reasoning and math-solving functionalities.
- **Streamlit**: For creating the interactive user interface.
- **Groq Gemma 2**: For AI-based reasoning and problem-solving.
- **Wikipedia API**: For data search and retrieval.

## Future Improvements

- Integrating additional data sources for broader knowledge retrieval.
- Expanding capabilities to handle more complex reasoning tasks.
- Optimizing the backend for faster response times.

Feel free to contribute and enhance this project!
