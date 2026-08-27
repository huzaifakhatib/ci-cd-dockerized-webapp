fROM python:3.9-slim

WORKDIR /app

# requirements.txt is inside app/app/
COPY app/app/requirements.txt .

RUN pip install --no-cache-dir -r requirements.txt

# Copy your application code
COPY app/app.py .

CMD ["python", "app.py"]
