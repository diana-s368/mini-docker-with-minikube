# Dockerfile 
FROM python:3.8-slim 

#Устанавливаем рабочую директорию в контейнер
WORKDIR /app

#Копируем все фацлы проекта в контейнер 
COPY . /app

#Устанавливаем зависимости 
RUN pip install -r requirements.txt

#открываем порт 5000
EXPOSE 5000

#запускаем приложение
CMD ["python", "app.py"]
