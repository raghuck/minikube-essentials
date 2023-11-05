# Use the official Python image
FROM python:3.9-slim

# Set the working directory
WORKDIR /app

# Copy the Python app into the container
COPY app.py /app/

# Install Flask
RUN pip install flask

# Expose port 8080
EXPOSE 8080

# Run the app
CMD ["python", "app.py"]