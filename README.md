Real-Time SWOT, Sentiment & Financial Analysis using RAG + Cohere

This project implements a Real-Time Business Intelligence Framework that automatically generates SWOT Analysis, Sentiment Insights, Competitor Intelligence, and Financial Analysis for any company using Retrieval-Augmented Generation (RAG) and Cohere LLMs.
The system converts live, unstructured data from multiple sources into clean, explainable, and evidence-based strategic insights, displayed through an interactive Streamlit dashboard.


🚀 Key Features
🔍 1. Automated RAG-Based SWOT Analysis

Uses Cohere Command-R+ LLM for structured SWOT generation.

Retrieves real-time evidence from NewsAPI, Twitter/X, Reddit, and Finnhub.

Embeds all text using Cohere embed-english-v3 for semantic retrieval.

Produces verifiable, context-aware SWOT instead of hallucinated responses.

😀 2. Sentiment Analysis (Real-Time)

Computes sentiment polarity (Positive / Negative / Neutral) for all retrieved documents.

Generates a Sentiment Score (0–100) and sentiment distribution charts.

Helps validate whether the market tone supports the SWOT insights.

💸 3. Financial Analysis Integration

Retrieves live financial metrics (P/E ratio, revenue growth, market cap, analyst rating).

Combines narrative insights with quantitative evidence.

Shows financial trend graphs and KPI cards inside the dashboard.

🆚 4. Competitor Intelligence

Detects competitors using NER and co-occurrence analysis.

Displays top competitors with comparative metrics (market cap, revenue growth, etc.).

Highlights threats and opportunities emerging from the competitive landscape.

🔗 5. Multi-Source Real-Time Data Retrieval

Integrates:

NewsAPI → news & press releases

Twitter/X API → public opinion

Reddit API → community sentiment

Finnhub API → financial stats

Ensures all insights remain up-to-date at every user query.

📊 6. Streamlit Interactive Dashboard

Displays SWOT quadrants

Radar charts

Sentiment trends

Competitor graphs

Financial metric panels

Downloadable JSON reports
