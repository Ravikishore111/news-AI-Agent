# 🌍 Global News Summarizer using CrewAI

This project uses **CrewAI** agents to automatically fetch and summarize the **top 5 global news stories**.  
It leverages:
- [CrewAI](https://github.com/joaomdmoura/crewai) for creating AI-powered agents.
- [Firecrawl](https://www.firecrawl.dev/) for web search.
- Google Gemini API for language model tasks.

---

## 🚀 Features
- Fetches the latest **global news topics** automatically.
- Summarizes each story into **concise, easy-to-read bullet points**.
- Modular agent-based architecture for **researching** and **summarizing**.
- Built to run on **Google Colab** or locally.

---

## 🛠️ Installation

1. Clone this repository:
   ```bash
   git clone https://github.com/your-username/news-summarizer.git
   cd news-summarizer
   ```

2. Install dependencies:
   ```bash
   pip install -r requirements.txt
   ```

---

## 🔑 API Keys Setup
You need the following API keys:
- **Google Gemini API Key**
- **Firecrawl API Key**

Set them as environment variables before running:
```bash
export GEMINI_API="your_gemini_api_key"
export FIRECRAWL_API_KEY="your_firecrawl_api_key"
```

Or in **Google Colab**, store them using:
```python
from google.colab import userdata
userdata.get("GEMINI_API")
userdata.get("FIRECRAWL_API_KEY")
```

---

## ▶️ Usage
Run the script:
```bash
python news(using_crew).py
```

This will:
1. Search for the latest global news (via Firecrawl).
2. Summarize the news into concise notes.

Output:  
```
Top 5 News Stories:
1. Ukraine War — Key developments and impact.
2. Israel-Hamas Conflict — Humanitarian situation.
3. Global Economy — Inflation and recession concerns.
4. Climate Change — Extreme weather events.
5. Artificial Intelligence — Rapid advancements and ethics.
```

---

## 📂 Project Structure
```
├── news(using_crew).py     # Main script
├── README.md               # Project documentation
└── requirements.txt        # Dependencies
```

---

## 🤝 Contributing
Pull requests are welcome.  
For major changes, please open an issue first to discuss what you would like to change.

---

## 📜 License
This project is licensed under the MIT License.
