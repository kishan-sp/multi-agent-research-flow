# Multi-Agent Research Flow (n8n)

A 5-agent research pipeline triggered via Telegram. Chains topic strategy, 
problem definition, web search (Tavily), fact verification (SIFT), 
narrative synthesis, and QC into a single automated research brief.

**Stack:** n8n · Groq (LLaMA 3.3-70b) · Tavily · Telegram

**Setup:** Add your API keys — Groq, Tavily, Telegram Bot — as n8n credentials. 
Set TAVILY_API_KEY as an environment variable.
