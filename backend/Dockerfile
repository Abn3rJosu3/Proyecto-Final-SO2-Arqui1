FROM python:3.9-slim

WORKDIR /app

COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# Copiar TODO el proyecto (backend/, frontend/, database/)
COPY . /app/

WORKDIR /app/backend

CMD ["python", "app.py"]
