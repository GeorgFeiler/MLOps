# Использование официального образа Python в качестве базового
FROM python:3.8-slim

# Установка рабочего каталога в контейнере
WORKDIR /app

# Копирование файла зависимостей и установка зависимостей
COPY requirements.txt ./
RUN pip install --no-cache-dir -r requirements.txt

# Копирование исходного кода в контейнер
COPY . .

# Указание порта, который будет открыт
EXPOSE 5000

# Команда для запуска приложения
CMD ["python", "./app.py"]
