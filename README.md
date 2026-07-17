# ResearchMind – Multi-Agent AI Research Assistant

ResearchMind is a multi-agent research system built with LangChain and Streamlit. It combines specialized AI agents for web search, content extraction, report generation, and critical review to produce high-quality research reports on any topic through an elegant web interface.

## Features

* Web search agent for gathering recent and reliable information.
* Reader agent that scrapes and extracts detailed content from selected sources.
* Writer chain that synthesizes findings into a structured research report.
* Critic chain that evaluates the report and provides actionable feedback.
* Modern Streamlit interface with downloadable Markdown reports.

## Architecture

1. **Search Agent** – Collects relevant information from the web.
2. **Reader Agent** – Scrapes and summarizes the most useful source.
3. **Writer Chain** – Produces a professional report with an introduction, key findings, conclusion, and references.
4. **Critic Chain** – Scores the report and highlights strengths and areas for improvement.

## Installation

```bash
git clone https://github.com/Indra45-git/multi-agent-AI-research-assistant.git
cd multi-agent-AI-research-assistant
pip install -r requirements.txt
```

Create a `.env` file containing your API keys:

```env
MISTRAL_API_KEY=your_key_here
TAVILY_API_KEY=your_key_here
```

## Running the Application

Launch the Streamlit interface:

```bash
streamlit run app.py
```

Alternatively, run the command-line pipeline:

```bash
python pipeline.py
```

## Tech Stack

* Python
* LangChain
* Mistral AI
* Tavily Search
* Streamlit
* BeautifulSoup

## License

This project is distributed under the terms of the included LICENSE file.

The project implements a four-stage research workflow using LangChain agents and a Streamlit frontend, with web search and scraping tools backed by Tavily and BeautifulSoup.
