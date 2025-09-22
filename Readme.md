# Financial Agentic AI

Financial_Agentic_AI is a Python-based project that leverages AI agents to perform tasks such as web searches and financial data analysis. It uses the `phi` library for agent creation and management, along with tools like `yfinance` and `duckduckgo-search` for specific functionalities.

## Features

- **Web Search Agent**: Searches the web for information and includes sources in the response.
- **Finance AI Agent**: Provides financial data, including stock prices, analyst recommendations, company information, and news, displayed in table format.
- **Multi-Agent Collaboration**: Combines multiple agents to handle complex queries.

## Project Structure

- `playground.py`: Main entry point for running the playground app.
- `financial_agent.py`: Script demonstrating the use of multiple agents for financial and web search tasks.
- `.env`: Environment variables, including API keys.
- `requirements.txt`: List of dependencies required for the project.


## Installation

1. Clone the repository:
   ```bash
   git clone <repository-url>
   cd AgenticAi
   ```
2. Create a virtual environment and activate it:
    ```bash
    python -m venv venv
    source venv/bin/activate
    # On Windows: venv\Scripts\activate
    ```
3. Install dependencies:
    ```bash
    pip install -r requirements.txt
    ```
4.Set up the .env file with your API keys:
  ```bash
    PHI_API_KEY="your_phi_api_key"
    GROQ_API_KEY="your_groq_api_key"
  ```

