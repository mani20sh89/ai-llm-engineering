# AI Website Summariser

**Author:** Manish Kundu

## Overview

AI Website Summariser is a Python-based project that extracts readable content from a webpage and uses a Large Language Model (LLM) to generate a concise, easy-to-read summary.

The project explores how web scraping, prompt engineering, and LLM APIs can be combined to build a practical AI application.

## Features

- Fetches content from public webpages.
- Extracts readable text using Beautiful Soup.
- Generates concise summaries using the OpenAI API.
- Includes URL validation and error handling.
- Uses environment variables to keep API credentials out of the source code.

## Tech Stack

- **Python** — application logic
- **OpenAI API** — AI-powered summarisation
- **Requests** — fetching webpage content
- **Beautiful Soup** — HTML parsing
- **Jupyter Notebook** — experimentation and documentation

## Getting Started

### 1. Clone the repository

```bash
git clone <your-repository-url>
cd <your-repository-folder>
```

Replace the placeholders with your actual GitHub repository URL and folder name.

### 2. Install dependencies

```bash
python -m pip install openai requests beautifulsoup4 python-dotenv
```

### 3. Configure your API key

Create a `.env` file in the project directory:

```text
OPENAI_API_KEY=your_api_key_here
OPENAI_MODEL=gpt-4.1-mini
```

Replace the placeholder with your own API key. **Never commit your `.env` file or expose your API key publicly.**

### 4. Run the notebook

Open `ai-website-summariser-manish-kundu.ipynb` in Jupyter Notebook or VS Code, configure your environment, and run the cells in order.

Change the example URL to a webpage you are permitted to access and summarise.

## Learning Objectives

- Understand the basic workflow of an LLM-powered application.
- Extract and process webpage content with Python.
- Design prompts for accurate, concise summaries.
- Integrate an external AI API.
- Handle invalid URLs, request failures, and empty responses.
- Apply basic practices for API key management.

## Limitations

- Some websites block automated requests or require JavaScript to render their content.
- Very long pages may be truncated before summarisation.
- Summary quality depends on the extracted text and the language model.
- API usage may incur costs.

## Future Improvements

- Add support for summarising long webpages in chunks.
- Save summaries to Markdown files.
- Add automated tests.
- Track API usage and estimated cost.
- Build a simple web interface.

## Author

**Manish Kundu**

This repository is part of my ongoing exploration of AI engineering, Python, and practical LLM applications.
