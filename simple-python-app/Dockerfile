FROM python:3.11

WORKDIR /app

COPY requirements.txt .
RUN pip install -r requirements.txt

COPY . .  # Copies everything from the build context

# CMD ["python", "your_script.py"]  # Or your application's startup command
