# ToDoList

## Установка

```bash
python -m venv venv
source venv/bin/activate  # Linux/macOS
venv\Scripts\activate     # Windows
pip install -r requirements.txt

Запуск NATS сервера 
.\nats-server.exe

Запуск приложения
uvicorn main:app --reload
