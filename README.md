# online магазин на Django

> **ВАЖНО**: Этот проект все еще находится в стадии разработки. Некоторые функции могут быть недоступны или работать нестабильно.

![screenshot1](https://github.com/khanzadalo/El.Market/assets/151526280/7a532378-e13d-4080-a51f-655c93b4d602)


Этот проект представляет собой онлайн-магазин, созданный с использованием Django, Python и JavaScript.
---
## Основные функции
-  Просмотр списка товаров
-  Добавление товаров в корзину
- Оформление заказа
-  Управление заказами (для администраторов)
---
## Технологии
- Python
- Django
- Django REST framework
- PostgreSQL

---
## Настройка
Для начала работы с проектом вам потребуется клонировать репозиторий на свой компьютер. Вы можете сделать это, используя следующие команды:

```bash
git clone https://github.com/khanzadalo/AgroSkillApi.git
cd AgroSkillApi
python -m venv venv
source venv/bin/activate Linux
venv\Scripts\activate   Windows
pip install -r requirements.
```
---
## .env file
Создайте файл .env и укажите в нем необходимые переменные окружения:
```
SECRET_KEY=your-secret-key
DEBUG=True
DB_NAME=your-database-name
DB_USER=your-database-user
DB_PASSWORD=your-database-password
DB_HOST=localhost
STRIPE_LIVE_PUBLIC_KEY=your-stripe-public-key
STRIPE_LIVE_SECRET_KEY=your-stripe-secret-key

```
---
## Запуск проекта
После создания файла .env, вы можете запустить проект, используя следующие команды:
```bash
python manage.py migrate
python manage.py createsuperuser(insert user name and password)
python manage.py runserver
```
Теперь вы можете открыть веб-браузер и перейти по адресу http://localhost:8000 для просмотра вашего сайта.

---
