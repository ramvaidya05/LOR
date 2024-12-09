# Base image with Python 3.9
FROM python:3.9-slim

# Set the working directory in the container
WORKDIR /app

# Copy application files into the container
COPY . /app

# Install dependencies
RUN pip install --no-cache-dir pandas numpy matplotlib flask scikit-learn

# Expose the port the app runs on
EXPOSE 5000

# Run the Flask application
CMD ["python", "project_flask.py"]
