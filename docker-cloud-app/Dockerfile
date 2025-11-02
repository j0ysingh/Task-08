# 1️⃣ Use a small Python image
FROM python:3.10-slim

# 2️⃣ Set working directory inside container
WORKDIR /app

# 3️⃣ Copy dependency file and install Flask
COPY requirements.txt .
RUN pip install --no-cache-dir -r requirements.txt

# 4️⃣ Copy the app code
COPY app.py .

# 5️⃣ Expose port 8080
EXPOSE 8080

# 6️⃣ Command to start the app
CMD ["python", "app.py"]
