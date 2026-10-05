# OHSL Chat Bot

## Overview
This project is an **AI-powered Chatbot** developed using **LangChain**, **LLaMA**, and **Gradio**. It integrates **LLM-based search engines** to improve conversational accuracy and user interactions. The chatbot also scrapes and processes web data for enhanced query responses.

## Key Features
- Uses **LLaMA-based LLMs** for contextual and accurate replies.
- Implements **LangChain** for seamless AI integration.
- Scrapes websites using **BeautifulSoup** and organizes data efficiently.
- Converts extracted data into vector embeddings for **semantic search**.
- Built with a **Gradio-based interface** for real-time user interactions.

## Technologies Used
- **LangChain** – Framework for integrating LLMs into applications.
- **LLaMA 2-7B** – Powerful model for AI-powered conversational agents.
- **BeautifulSoup** – Web scraping for retrieving relevant documents.
- **Hugging Face Embeddings** – Converts text into vector representations.
- **ChromaDB** – Vector database for efficient retrieval.
- **Gradio** – Provides a user-friendly web-based chatbot UI.

## Installation
1. Clone the repository:
   ```sh
   git clone https://github.com/yourusername/yourrepo.git
   cd yourrepo
   ```

2. Install dependencies:
   ```sh
   pip install -r requirements.txt
   ```

3. Run the application:
   ```sh
   python chatbot.py
   ```

## Future Improvements
- Integrating multi-language support.
- Enhancing chatbot memory for long conversations.
- Improving vector retrieval for better query responses.

## License
MIT License
