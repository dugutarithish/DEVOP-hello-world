From python:3.9-slim

WORKDIR  /app


copy requirement.txt
RUN pip install --no-cache-dir -r requirements.txt

# Copy app code
COPY . .

# Expose port
EXPOSE 5000

# Run app
CMD ["python", "app.py"]
