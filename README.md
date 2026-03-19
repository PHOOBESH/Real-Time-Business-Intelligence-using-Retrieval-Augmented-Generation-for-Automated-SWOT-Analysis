
```markdown id="swotrag01"
# 📊 Real-Time Business Intelligence Platform  
### 🔍 SWOT, Sentiment & Financial Analysis using RAG + Cohere

An advanced **Real-Time Business Intelligence System** that generates **SWOT Analysis, Sentiment Insights, Competitor Intelligence, and Financial Analysis** using **Retrieval-Augmented Generation (RAG)** with **Cohere LLMs**.

The system transforms **live, unstructured data** into **accurate, explainable, and evidence-backed strategic insights**, presented through an **interactive Streamlit dashboard**.

---

## 🚀 Key Highlights

- ⚡ Real-time, data-driven SWOT analysis (no hallucinations)
- 🔗 Multi-source data integration (News, Social Media, Finance)
- 🤖 RAG-based architecture using Cohere LLM
- 📊 Interactive dashboard with visual analytics
- 🧠 Combines qualitative + quantitative intelligence

---

## 🔍 Core Features

### 🧠 1. Automated RAG-Based SWOT Analysis

- Uses **Cohere Command-R+** for structured SWOT generation  
- Retrieves real-time context from:
  - 📰 NewsAPI  
  - 🐦 Twitter/X  
  - 💬 Reddit  
  - 💹 Finnhub  
- Embeds data using **Cohere embed-english-v3**  
- Ensures **context-aware, verifiable insights** (avoids hallucination)

---

### 😀 2. Real-Time Sentiment Analysis

- Classifies data into:
  - Positive  
  - Negative  
  - Neutral  
- Generates:
  - 📈 Sentiment Score (0–100)  
  - 📊 Distribution charts  
- Validates alignment between **market perception and SWOT**

---

### 💸 3. Financial Intelligence

- Retrieves real-time financial metrics:
  - P/E Ratio  
  - Revenue Growth  
  - Market Capitalization  
  - Analyst Ratings  
- Combines:
  - 📊 Quantitative KPIs  
  - 🧠 Narrative insights  
- Displays:
  - Trend graphs  
  - KPI dashboards  

---

### 🆚 4. Competitor Intelligence

- Detects competitors using:
  - Named Entity Recognition (NER)  
  - Co-occurrence analysis  
- Provides:
  - 📊 Comparative metrics  
  - 📉 Competitive positioning  
- Identifies:
  - Threats  
  - Opportunities  

---

### 🔗 5. Multi-Source Data Retrieval

Integrates real-time data from:

- 📰 **NewsAPI** → News & press releases  
- 🐦 **Twitter/X API** → Public sentiment  
- 💬 **Reddit API** → Community discussions  
- 💹 **Finnhub API** → Financial data  

➡️ Ensures **fresh, up-to-date insights for every query**

---

### 📊 6. Interactive Streamlit Dashboard

- SWOT quadrant visualization  
- 📡 Real-time sentiment charts  
- 🆚 Competitor comparison graphs  
- 💸 Financial KPI panels  
- 📉 Trend analysis  
- 📥 Downloadable JSON reports  

---

## 🛠️ Tech Stack

### 🔹 Backend & AI
- Python  
- Cohere LLM (Command-R+)  
- Cohere Embeddings (embed-english-v3)  
- RAG Architecture  

### 🔹 Data Sources
- NewsAPI  
- Twitter/X API  
- Reddit API  
- Finnhub API  

### 🔹 Frontend
- Streamlit  
- Plotly / Matplotlib (visualizations)  

---

## 🏗️ System Architecture

```

User Query
↓
Multi-Source Data Retrieval (News, Twitter, Reddit, Finance)
↓
Text Preprocessing + Embedding (Cohere)
↓
Vector Retrieval (RAG Pipeline)
↓
Cohere LLM (Command-R+)
↓
SWOT + Sentiment + Competitor + Financial Insights
↓
Streamlit Dashboard (Visualization)

````id="archswot01"

---

## ⚙️ How It Works

1. User enters a **company name**
2. System fetches **real-time data** from multiple sources
3. Data is:
   - Cleaned  
   - Embedded  
   - Stored for retrieval  
4. RAG pipeline retrieves **relevant context**
5. Cohere LLM generates:
   - SWOT analysis  
   - Insights  
6. Additional modules compute:
   - Sentiment  
   - Financial metrics  
   - Competitor analysis  
7. Results displayed via **interactive dashboard**

---

## 🚀 Installation & Setup

### 🔧 Prerequisites
- Python 3.8+
- API keys (Cohere, NewsAPI, Finnhub)

---

### 📥 Clone Repository

```bash
git clone https://github.com/your-username/real-time-swot-rag.git
cd real-time-swot-rag
````

---

### 📦 Install Dependencies

```bash id="install01"
pip install -r requirements.txt
```

---

### 🔑 Set Environment Variables

```bash id="env01"
export COHERE_API_KEY="your-cohere-api-key"
export NEWS_API_KEY="your-news-api-key"
export FINNHUB_API_KEY="your-finnhub-api-key"
```

---

### ▶️ Run the Application

```bash id="run01"
streamlit run app.py
```

---

## 📊 Output Examples

* SWOT Analysis (Strengths, Weaknesses, Opportunities, Threats)
* Sentiment Score + Charts
* Financial KPI Dashboard
* Competitor Comparison
* Downloadable Insights Report

---

## 📈 Performance & Impact

* 📊 Reduces manual market research effort significantly
* ⚡ Provides **real-time decision intelligence**
* 🎯 Improves strategic insight accuracy using RAG
* 🔍 Eliminates hallucinated outputs via evidence-based retrieval

---

## 🔒 Security & Best Practices

* API keys secured via environment variables
* Input validation for all queries
* Modular and scalable architecture
* Designed for production-ready deployment

---

## 🚀 Future Enhancements

* Integration with vector databases (Weaviate / Pinecone)
* Real-time streaming pipelines (Kafka)
* Advanced forecasting models
* Industry-specific SWOT templates
* Dashboard personalization

---

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Commit changes
4. Submit a Pull Request

---

## 📝 License

MIT License

---

## 👨‍💻 Author

**Phoobesh S**
M.Tech Integrated (CSE) – Pre-Final Year
Interested in AI, RAG Systems, and Data-Driven Decision Platforms

---

## ⭐ Support

If you found this project useful, give it a ⭐ on GitHub!

```



Just tell 👍
```
