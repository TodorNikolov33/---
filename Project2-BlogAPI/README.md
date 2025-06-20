# 📝 BlogAPI – RESTful API за блог платформа

BlogAPI е бекенд система, изградена с FastAPI, предназначена за управление на блог платформа. Потребителите могат да създават акаунти, да публикуват статии, да коментират публикации и да използват JWT автентикация.

---

## 🚀 Основни функции

- 🔐 Регистрация и логин на потребители с JWT
- ✍️ CRUD операции за блог постове
- 💬 Коментари към публикации
- 📄 Автоматична документация (Swagger UI и Redoc)
- 🧪 Готова за разширение с лайкове, тагове и категории

---

## 🧰 Технологии

- **Python 3.10+**
- **FastAPI**
- **Pydantic**
- **SQLAlchemy (или in-memory dict за демо цели)**
- **JWT (via `python-jose`)**
- **Uvicorn** – за стартиране на сървъра

---

## 📂 Структура на проекта


---

## 📦 Инсталация

```bash
# 1. Клонирай проекта
git clone https://github.com/yourusername/blogapi.git
cd blogapi

# 2. Създай виртуална среда (по избор)
python -m venv venv
source venv/bin/activate  # или venv\Scripts\activate за Windows

# 3. Инсталирай зависимостите
pip install -r requirements.txt

# 4. Стартирай приложението
uvicorn app.main:app --reload

