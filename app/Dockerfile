FROM python:3.13.9

WORKDIR /app

COPY requirements.txt .

RUN pip install -r requirements.txt

COPY main.py .

CMD ["uvicorn","app.main:app"]