- 👋 Hi, I’m @Gamil745
- 👀 I’m interested in ...
- 🌱 I’m currently learning ...
- 💞️ I’m looking to collaborate on ...
- 📫 How to reach me ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
import requests
from bs4 import BeautifulSoup
import telegram
import time

# استبدل بـ token الخاص ببوتك و ID القناة
bot_token = 'AAEGgK9vjDZh0itSJd8ArknwIucORGKDrS4'
chat_id = '7182750651'

def get_news(keywords, sources):
    # ... (باقي الدالة كما هي)

def send_to_telegram(text):
    # ... (باقي الدالة كما هي)

# الكلمات المفتاحية والمواقع المراد البحث فيها
keywords = ['الغاز الطبيعي', 'أدنوك', 'أدنوك للغاز', 'غاز', 'طاقة']
sources = ['wam.ae', 'skynewsarabia.com', 'albayan.ae', 'khaleejtimes.com', 'alarabiya.net', 'cnbcarabia.com', 'forbesmiddleeast.com', 'france24.com', 'aawsat.com', 'attaqa.net', 'reuters.com', 'bloomberg.com']

while True:
    news = get_news(keywords, sources)
    for link in news:
        send_to_telegram(link)
    time.sleep(600)  # الانتظار 10 دقائق
<!---
Gamil745/Gamil745 is a ✨ special ✨ repository because its `README.md` (this file) appears on your GitHub profile.
You can click the Preview link to take a look at your changes.
--->
