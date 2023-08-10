[![Typing SVG](https://readme-typing-svg.demolab.com?font=Fira+Code&pause=1000&color=28F70E&width=435&lines=%D0%9F%D0%BB%D0%B0%D0%BD%D0%B8%D1%80%D0%BE%D0%B2%D1%89%D0%B8%D0%BA+%D0%B7%D0%B0%D0%B4%D0%B0%D1%87)](https://git.io/typing-svg)

Приложение для планирования своих задач.

#### Локальный запуск проекта

- Склонировать репозиторий:

```bash
   git clone git@github.com:zsv28/taski.git
```

- В папке с проектом создать и активировать виртуальное окружение:

Команда для установки виртуального окружения на Mac или Linux:

```bash
   python3 -m venv env
   source env/bin/activate
```

Команда для Windows:

```bash
   python -m venv venv
   source venv/Scripts/activate
```

- Перейти в директорию backend:

```bash
   cd backend
```

- Установить зависимости из файла requirements.txt:

```bash
   pip install -r requirements.txt
```

```bash
   python manage.py migrate
```

- Запустить локальный сервер:

```bash
   python manage.py runserver
```
