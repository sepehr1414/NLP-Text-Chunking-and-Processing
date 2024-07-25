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
The NLP Text Chunking and Processing project is designed to overcome the challenges associated with analyzing and processing large volumes of text data using state-of-the-art Language Models (LLMs) like GPT. Many LLMs have token limits that restrict the amount of text they can process in a single operation. This project addresses this limitation by implementing an intelligent text splitting and processing pipeline.
Key aspects of the project include:

Intelligent Text Splitting: The core of this project is its ability to break down large text inputs into smaller, semantically coherent chunks. This is achieved through advanced Natural Language Processing techniques that consider sentence structure, context, and semantic relationships to ensure that each chunk maintains its meaning and relevance.
Token-Aware Processing: The system is designed to be aware of token limits imposed by various LLMs. It carefully measures the length of text inputs and chunks them accordingly, ensuring that each piece fits within the specified token limit while maximizing the use of available tokens.
Semantic Coherence Preservation: Unlike simple character or word-based splitting methods, this project employs sophisticated algorithms to maintain the semantic integrity of the text. It uses techniques like cosine similarity and TF-IDF vectorization to ensure that related content stays together, preserving the overall meaning and context of the original text.
LLM Integration: The project seamlessly integrates with OpenAI's GPT models, allowing for powerful text analysis, generation, and processing tasks. It's designed to be flexible, potentially allowing integration with other LLMs in the future.
Scalability: Whether you're working with a short paragraph or a lengthy document, the system adapts to process texts of varying lengths efficiently. This scalability makes it suitable for a wide range of applications, from content analysis to document summarization.
Customizability: The project is built with modularity in mind, allowing users to easily adjust parameters such as chunk size, similarity thresholds, and processing methods to suit their specific needs and use cases.

Potential applications of this project include:

Document Summarization: Breaking down large documents for comprehensive summarization.
Content Analysis: Analyzing lengthy articles or reports for key themes and insights.
Text Generation: Creating coherent long-form content by processing it in manageable chunks.
Information Extraction: Extracting specific information from large textual datasets.
Research and Data Mining: Processing and analyzing large corpora of text data for research purposes.

By bridging the gap between large text inputs and the token limitations of advanced language models, this project opens up new possibilities for text processing and analysis in various fields including content creation, data analysis, academic research, and more.
## Features

✂️ Smart text splitting into manageable chunks
📏 Text length measurement using token count
🔍 Similarity checking between text slices for coherent splitting
🤖 Integration with OpenAI's GPT models
📚 Flexible handling of both short and long text inputs
🧠 Semantic coherence preservation in text chunking
🔧 Customizable parameters for various use cases
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
