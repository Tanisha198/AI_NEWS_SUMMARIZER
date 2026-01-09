 📰 AI News Summarizer (Python)

This project is an AI-powered news summarization system built using Python and NLP.
It fetches real-time news articles using NewsAPI and generates short summaries using a transformer-based model.

Get your API Key from https://newsapi.org

 🔹 Features
- Fetches latest news based on user input
- Uses HuggingFace Transformer model for summarization
- Removes duplicate news articles
- Clean and readable output

 🔹 Technologies Used
- Python
- Transformers (DistilBART)
- NewsAPI
- Natural Language Processing (NLP)

🔹 Project Workflow
1. User enters a news topic
2. News articles are fetched from NewsAPI
3. Content is cleaned and filtered
4. AI model generates summaries
5. Final summarized news is displayed

 🔹 How to Run
```bash

pip install -r requirements.txt

python app.py
