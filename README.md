# NLP Text Chunking and Processing

![Python](https://img.shields.io/badge/python-3.6+-blue.svg)
![NLTK](https://img.shields.io/badge/NLTK-3.6-green.svg)
![scikit-learn](https://img.shields.io/badge/scikit--learn-0.24+-orange.svg)
![OpenAI](https://img.shields.io/badge/OpenAI-API-red.svg)

A Python-based NLP project for processing and analyzing large text inputs using advanced language models.

## Table of Contents

- [Description](#description)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies](#technologies)
- [Contributing](#contributing)
- [License](#license)

## Description

This project addresses the challenge of processing large text inputs that exceed the token limits of most Large Language Models (LLMs). It intelligently splits input text into smaller, semantically coherent chunks, processes them through an LLM, and combines the results for comprehensive analysis or generation tasks.

## Features

- ✂️ Smart text splitting into manageable chunks
- 📏 Text length measurement using token count
- 🔍 Similarity checking between text slices for coherent splitting
- 🤖 Integration with OpenAI's GPT models
- 📚 Flexible handling of both short and long text inputs

## Installation

1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/nlp-text-chunking.git
   cd nlp-text-chunking
   ```

2. Install required dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Set up your OpenAI API key:
   - Create a `.env` file in the project root
   - Add your API key:
     ```
     OPENAI_API_KEY=your_api_key_here
     ```

## Usage

1. Run the main script:
   ```sh
   python main.py
   ```

2. To process custom text:
   - Open `config.py`
   - Modify the `input_text` variable
   - Run `main.py` again

## Project Structure

- `config.py`: Configuration settings and sample input text
- `llm.py`: Handles OpenAI API interactions
- `npl_utils.py`: Provides NLP utility functions
- `main.py`: Orchestrates the text processing workflow

## Technologies

- [Python](https://www.python.org/)
- [NLTK](https://www.nltk.org/)
- [scikit-learn](https://scikit-learn.org/)
- [OpenAI API](https://openai.com/)
- [python-dotenv](https://github.com/theskumar/python-dotenv)

## Contributing

Contributions are welcome! Please feel free to submit a Pull Request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
