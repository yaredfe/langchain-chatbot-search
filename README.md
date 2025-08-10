# LangChain - Chat with Search (Streamlit Integration)

## Overview

This project integrates LangChain with Streamlit to create a chatbot that can interact with users, query Arxiv and Wikipedia, and perform web searches using DuckDuckGo. The chatbot is powered by the Groq API, allowing for seamless natural language processing and question answering.

### Features:
- **Arxiv Integration**: Query Arxiv for academic papers.
- **Wikipedia Integration**: Query Wikipedia for articles.
- **DuckDuckGo Integration**: Perform web searches for additional information.
- **Groq API**: Leverage Groq’s powerful language models to process queries.
- **Interactive UI**: Build a simple, interactive chat interface with Streamlit.
- **Real-time Feedback**: Display the thoughts and actions of the agent in real-time through Streamlit's interface.

## Setup and Installation

### Requirements
- Python 3.7+
- Streamlit
- LangChain
- Groq API
- Arxiv and Wikipedia API wrappers
- DuckDuckGo search functionality
- dotenv for environment variables management

### Install Dependencies

To get started, first clone the repository and install the required dependencies.

```bash
git clone <https://github.com/yaredfe/langchain-chatbot-search>
cd <langchain-chatbot-search>
pip install -r requirements.txt
