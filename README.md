# Library Books API

Лабка 4

## Возможности

- список книг
- книга по ID
- Добавление книги
- Обновление книги
- Удаление книги
- Проверка входных данных
- Обработка ошибки 404

## Установка

```bash
python -m venv venv
```

```powershell
.\venv\Scripts\Activate.ps1
```

установка:

```bash
python -m pip install fastapi "uvicorn[standard]"
```

## Запуск

```bash
python -m uvicorn main:app --reload
```

ссылка API:
http://127.0.0.1:8000/docs
