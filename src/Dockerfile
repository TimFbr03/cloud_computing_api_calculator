# Use an official Python image
FROM python:3.11-slim

# Set working directory
WORKDIR /app

# Copy only what's needed
COPY app.py .

# Install dependencies
RUN pip install flask

# Expose the Flask app port
EXPOSE 5000

# Run the app
CMD ["python", "app.py"]
