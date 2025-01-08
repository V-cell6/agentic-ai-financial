# agentic-ai-financial

# AI Finance and Web Search Agents

## Overview

This project provides a framework for AI agents designed to perform financial analysis and web searches. The system leverages tools such as YFinance for financial data, DuckDuckGo for web searches, and the Groq language model for intelligent responses. It also includes a playground interface for interactive usage of the agents.

## Features

### Finance AI Agent:
- Fetches stock prices, analyst recommendations, stock fundamentals, and company news.
- Displays data in tables for better readability.

### Web Search Agent:
- Searches the web for relevant information.
- Always includes sources in the output.

### Multi-Agent System:
- Combines the Finance AI Agent and Web Search Agent for collaborative tasks.
- Provides streamlined outputs for complex queries.

### Playground:
- A web-based interface to interact with the agents.
- Built using the `phi.playground` module.

## Requirements

The following Python packages are required to run this project:
- phidata
- python-dotenv
- yfinance
- packaging
- duckduckgo-search
- fastapi
- unicorn
- groq
- openai
