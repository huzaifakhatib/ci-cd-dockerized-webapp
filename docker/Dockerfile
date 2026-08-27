FROM python:3.9-slim

WORKDIR /app

# Copy requirements from the nested app/app folder
COPY app/app/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

# Copy the application code
COPY app/app.py .

CMD ["python", "app.py"]
