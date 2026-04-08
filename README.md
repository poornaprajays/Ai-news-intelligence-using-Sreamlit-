# 📰 AI News Intelligence Dashboard

### *Real-time insights. Zero noise. Powered by GPT-4o.*

The **AI News Intelligence Dashboard** is a next-generation news monitoring platform that goes beyond simple headlines. It uses advanced AI to summarize, analyze sentiment, and detect media bias in real-time, giving users complete situational awareness of the global news cycle (with a focus on **India 🇮🇳**).

![Streamlit](https://img.shields.io/badge/Streamlit-1.28+-FF4B4B?style=for-the-badge&logo=streamlit&logoColor=white)
![OpenAI](https://img.shields.io/badge/GPT--4o-Powered-412991?style=for-the-badge&logo=openai&logoColor=white)
![NewsAPI](https://img.shields.io/badge/NewsAPI-integrated-blue?style=for-the-badge)

---

## 🚀 Key Features

### 1. **Live Intelligence Feed** 📡
*   **India-First Default**: Automatically loads top 50 breaking stories from India.
*   **Smart Search**: Fallback mechanisms ensure you always get relevant results (Top Headlines → Everything Search).
*   **Auto-Categorization**: Sorts news into Politics, Tech, Business, Sports, and Health instantly.

### 2. **AI Power Tools** 🧠
*   **⚡ Smart Summarization**: Compresses long articles into bulleted key facts using **OpenRouter (GPT-4o)**.
*   **⚖️ Bias Detection**: AI analyzes framing to detect political leaning and hidden agendas.
*   **🌡️ Global Mood Gauge**: Real-time sentiment analysis (Optimistic vs Grim) of the entire news feed using **NLTK VADER**.

### 3. **Analytics Dashboard** 📊
*   **Trending Keywords**: Visualize the hottest topics (e.g., #Election, #Crypto, #SpaceX).
*   **Publisher Stats**: See which sources are dominating the narrative.

---

## 🛠️ Technology Stack

*   **Frontend**: Streamlit (Python)
*   **LLM Provider**: OpenRouter (GPT-4o)
*   **Sentiment Analysis**: NLTK VADER (Lightweight & Fast)
*   **Data Source**: NewsAPI (Official Client)
*   **Deployment**: Streamlit Community Cloud

---

## ⚙️ Installation & Setup

### 1. Clone the Repository
```bash
git clone https://github.com/yourusername/news-intelligence-dashboard.git
cd news-intelligence-dashboard
```

### 2. Install Dependencies
```bash
pip install -r requirements.txt
```

### 3. Configure API Keys
Create a `.env` file in the root directory:
```ini
NEWSAPI_KEY=your_newsapi_key_here
OPENROUTER_API_KEY=sk-or-v1-your_openrouter_key_here
```
*(Get keys from [newsapi.org](https://newsapi.org) and [openrouter.ai](https://openrouter.ai))*

### 4. Run the App
```bash
streamlit run app/streamlit_app.py
```

---

## 📂 Project Structure
```
ai-news-intelligence/
├── app/
│   ├── streamlit_app.py   # Main Router (Navigation)
│   ├── dashboard.py       # News Feed View
│   └── pages/
│       └── 1_Analytics.py # Analytics Dashboard
├── analysis/              # AI Logic (Bias, Sentiment)
├── preprocessing/         # News Fetching & Cleaning
└── requirements.txt       # Dependencies
```

---

## 🤝 Contributing
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.

---

*Built with ❤️ for the AI News Revolution....*
