# agentic-ai-tasks
AI Agents and Tools Collection
This repository contains five Jupyter notebooks demonstrating various AI-powered agents and tools. Each notebook focuses on a specific task or concept, ranging from booking systems to research agents and prompt engineering studies. These are designed to run in environments like Google Colab or local Jupyter setups.
Notebooks Overview
1. booking_agent.ipynb

Description: A booking agent application built with FastAPI, Gradio for the UI, and Twilio for SMS integration. It sets up a web server for handling bookings, possibly for reservations or appointments, with real-time interactions.
Key Features:

Installs and uses packages like FastAPI, Uvicorn, Pyngrok, Gradio, and Twilio.
Supports asynchronous operations and API endpoints for booking management.


Use Case: Ideal for building conversational booking systems with messaging support.
How to Run: Execute the cells to install dependencies and launch the Gradio interface. Use Ngrok for public exposure if needed.

2. at4.ipynb

Description: An Advanced RAG (Retrieval-Augmented Generation) Research Agent. This notebook creates a UI for conducting complex research queries with task delegation, multi-source analysis, and customizable depth/settings.
Key Features:

Widget-based interface for inputting research queries, selecting sources (e.g., web, X/Twitter), and enabling task delegation.
Generates reports with executive summaries, key findings, recommendations, and methodology.
Includes specialized worker agents for data analysis, trends, comparisons, impacts, and solutions.


Use Case: Useful for in-depth research on topics requiring multi-faceted analysis.
How to Run: Run the cells to display the research panel. Enter a query and click "Start Research" to generate results.

3. at2.ipynb

Description: A comparative study tool for LLM (Large Language Model) responses. It compares outputs generated from user prompts alone versus user prompts combined with system prompts.
Key Features:

Interactive UI with text areas for user and system prompts.
Displays comparison tables, detailed analyses, and key differences (e.g., structure, specificity, tone).
Uses mock LLM responses for demonstration.


Use Case: Helps understand the impact of system prompts on AI response quality and adherence to guidelines.
How to Run: Input prompts and click "Compare Responses" to view side-by-side analyses and tables.

4. task1.ipynb

Description: A Structured LLM Agent for generating formatted responses from user prompts. It enforces structured outputs like lists or tables based on detected query types.
Key Features:

Supports output formats: JSON, XML, CSV, Markdown Table, YAML.
Automatically infers schema from prompts (e.g., lists of items with attributes).
Mock LLM responses for structured data generation.


Use Case: Ensures consistent, parseable outputs from AI models for data extraction or reporting.
How to Run: Enter a prompt, select a format, and click "Generate Response" to see the structured output.

5. langchain (2).ipynb

Description: Printa's Web Search Agent, powered by Google Custom Search API (integrated with LangChain concepts). It allows refined web searches with context and output formatting.
Key Features:

UI for primary query, context, refinements, and result formats (Table, JSON, List, Markdown).
Uses real API calls to fetch and display search results with titles, links, and snippets.
Supports reset and multiple refinements for precise searching.


Use Case: Web research tool for quick, formatted information retrieval.
How to Run: Replace API key and Search Engine ID in the code, enter a query, add refinements if needed, and click "Search".

Requirements

Python: 3.10+
Jupyter/Colab: For running the notebooks.
Common Packages (installed via pip in notebooks):

ipywidgets, pandas, requests, gradio, fastapi, uvicorn, twilio, pyngrok, etc.
For langchain (2).ipynb: Google Custom Search API key and Engine ID required.


Install all via: pip install -r requirements.txt (create one by aggregating from notebooks if needed).

Setup and Usage

Clone the repository: git clone <repo-url>.
Open notebooks in Jupyter Lab/Notebook or Google Colab.
Run the first cell to install dependencies (if any).
Interact with the widget-based UIs in each notebook.
For API-dependent notebooks (e.g., booking_agent, langchain), provide your own API keys.

Notes

These notebooks use mock data/responses in places for demonstration; integrate real LLMs (e.g., OpenAI) for production.
Ensure compliance with API terms (e.g., Twilio, Google Search).
Contributions: Feel free to fork and PR improvements!

License
MIT License - Free to use and modify.
