FROM python:3.10

WORKDIR /app

COPY lab3/requirements.txt /app

RUN pip install -r requirements.txt

COPY lab3/app.py /app

CMD ["python3", "app.py"]
