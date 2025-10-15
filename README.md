# 📰 Weekly News Aggregator (Python + g4f)

Скрипт автоматически собирает и форматирует свежие новости за последнюю неделю по темам:  
**Маркетинг, Технологии, Реклама, Искусственный интеллект, Социальные сети.**

---

## 🚀 Установка и запуск

```bash
# 1️⃣ Клонировать проект
git clone https://github.com/nurgaliev-d/pythonDailyNews.git
cd <your-repo>

# 2️⃣ Создать виртуальное окружение
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate

# 3️⃣ Установить зависимости
pip install -r requirements.txt

# 4️⃣ Создать .env файл и добавить ключ от NewsAPI
echo "NEWS_API_KEY=ваш_ключ_сюда" > .env

# 5️⃣ Запустить скрипт
python main.py
