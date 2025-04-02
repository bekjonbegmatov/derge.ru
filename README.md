# 🌟 Derge - Платформа для программистов

**Derge** — это инновационная площадка, объединяющая лучшие возможности GitHub, Stack Overflow, Medium и Stepik. Это место, где разработчики могут публиковать проекты, обмениваться знаниями и получать помощь от ИИ.

## 🚀 Основные возможности
✔ **Социальная сеть программистов** — делитесь проектами, ведите блоги, обсуждайте технологии.
✔ **Форум вопросов и ответов** — аналог Stack Overflow с ИИ-помощником.
✔ **Автоматическая генерация документации** — быстро создавайте качественную документацию к коду.
✔ **Оптимизация кода** — анализ и рекомендации по улучшению кода с ИИ.
✔ **Интеграция с GitHub, Stack Overflow и LinkedIn**.
✔ **Поддержка API** — тестирование и документация API прямо в платформе.

## 🛠 Используемые технологии
🎯 **Backend**: Django, Django Rest Framework  
🎨 **Frontend**: Vue.js  
🗄 **База данных**: PostgreSQL  
🔑 **Аутентификация**: JWT (SimpleJWT)  
⚡ **Кэширование**: Redis  
📂 **Файловое хранилище**: S3 / локальное  
📜 **Документация API**: Swagger / Redoc  
🐳 **Контейнеризация**: Docker, Docker Compose  
🚀 **Развертывание**: Nginx + Gunicorn  

---

## 📦 Установка и запуск
### 🔹 1. Клонирование репозитория
```bash
git clone https://github.com/bekjonbegmatov/derge.ru.git
cd derge.ru
```
### 🔹 2. Настройка окружения
```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate  # Windows
pip install -r requirements.txt
```
### 🔹 3. Конфигурация `.env`
Создайте `.env` в корне проекта:
```env
SECRET_KEY=your_secret_key
DEBUG=True
DATABASE_URL=postgres://user:password@localhost:5432/derge_db
```
### 🔹 4. Применение миграций
```bash
python manage.py migrate
python manage.py createsuperuser
```
### 🔹 5. Запуск проекта
```bash
python manage.py runserver
```
📌 Теперь проект доступен по адресу: [`http://127.0.0.1:8000/`](http://127.0.0.1:8000/)

---

## 📖 API
🔍 API документация доступна по адресам:
- 📜 **Swagger**: [`/api/docs/swagger/`](http://127.0.0.1:8000/api/docs/swagger/)
- 📘 **Redoc**: [`/api/docs/redoc/`](http://127.0.0.1:8000/api/docs/redoc/)

---

## 🐳 Запуск в Docker
```bash
docker-compose up --build
```

---

## 🤝 Вклад в проект
Любые предложения приветствуются! 🚀 Открывайте **issue** или создавайте **pull request**. 

💡 **Понравился проект? Оставьте ⭐ на GitHub!**

---

### 📌 Автор: [Bekjon Begmatov](https://github.com/bekjonbegmatov)

