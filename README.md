# X Sentiment Analysis Bot

Discord bot untuk analisis sentimen tweet menggunakan NLP.

## 🚀 Fitur
- Real-time Twitter crawling (advanced search)  
- Preprocessing & normalisasi teks bahasa Indonesia  
- Analisis sentimen dengan VADER  
- Ekspor hasil ke CSV  
- Laporan otomatis ke Discord  

## 🛠 Instalasi & Jalankan
```bash
git clone https://github.com/septionfl/x-sentiment-analysis.git
cd x-sentiment-analysis
pip install -r requirements.txt

# Twitter Configuration
TWITTER_AUTH_TOKEN=your_twitter_auth_token_here

# Discord Configuration  
DISCORD_TOKEN=your_discord_bot_token_here
DISCORD_WEBHOOK_URL=your_discord_webhook_url_here

# Application Settings
DEFAULT_LIMIT=100
DEFAULT_FILENAME=hasil_crawling.csv
DEFAULT_SEARCH_QUERY=from:tanyakanrl lang:id until:2024-10-29 since:2024-10-01
LOG_LEVEL=INFO

python bot.py
