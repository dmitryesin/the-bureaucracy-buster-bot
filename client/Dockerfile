FROM python:3.13.3-slim

WORKDIR /client

COPY client .
COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "main.py"]