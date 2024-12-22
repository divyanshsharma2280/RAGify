Code Assistant Bot

Overview:
This Code Assistant Bot is designed to generate accurate and up-to-date code responses using the latest documentation of frameworks and libraries. Unlike traditional language models that rely on outdated training data, this bot scrapes live documentation, converts it into embeddings, and uses a locally downloaded large language model (LLM) to generate contextually accurate answers.

Features:
1. Real-time Accuracy: The bot scrapes up-to-date documentation directly from the website (e.g., Django) before answering questions.
2. Embedding-based Search: It converts the scraped content into vector embeddings, ensuring that responses are contextually accurate and up to date.
3. Locally Run LLM: The bot runs a large language model on your local device, making it customizable and private.
4. Customizable Scraping: Users can input the link of the website they want to scrape for documentation, and the bot will process the first 100 pages to generate code responses.

How It Works
The bot operates in two main parts:

Web Scraping and Documentation Processing

The user provides a URL of a website (for example, Django documentation).
The bot scrapes the first 100 pages of the website.
The scraped content is converted into a PDF for easy reference.
Vector embeddings are generated from the content for quick retrieval.
Question-Answering and Code Generation

The vector embeddings, along with the local LLM, are used to answer questions and generate code based on the latest documentation.
The LLM is downloaded and run locally to ensure privacy and performance.
Prerequisites
Python 3.8+
[LLM model file] downloaded on the local device (OLLAMA IS USED IN THIS CASE).
