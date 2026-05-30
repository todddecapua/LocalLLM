# LocalLLM

# Local LLM Financial Trend Analyzer 📈🤖

An educational, hands-on guide demonstrating how to build a private, localized multi-agent AI system for the Financial Services industry. This project uses **Ollama** and **CrewAI** to aggregate financial news, analyze market sentiment, and compile an executive summary of the "Top 5 Financial Trends" for personal investors and advisors—completely on your local machine.

## Architecture Overview



The system establishes a team of three specialized AI agents working sequentially:
1. **Financial News Scraper (Tool-enabled):** Aggregates raw textual data from financial RSS feeds.
2. **Market Sentiment Analyst:** Processes data to identify emerging macroeconomic themes.
3. **Executive Financial Advisor:** Synthesizes findings into a polished, client-ready report.

## Prerequisites

Ensure you have the following installed before beginning:
* Python 3.10 to 3.13
* [Ollama](https://ollama.com/) (Local LLM runtime)

## Step-by-Step Setup

### Step 1: Install & Launch the Local LLM
Open your terminal and pull a highly capable, instruction-tuned local model. We recommend `llama3` (or `qwen2.5:14b` for deep financial reasoning):

```bash
# Download and run the local model
ollama run llama3
