FROM python:3.13.3-slim

WORKDIR /server

COPY server .
COPY requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

CMD ["python", "main.py"]