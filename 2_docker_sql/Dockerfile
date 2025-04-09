# Use the official Python image as the base image
FROM python:3.9

# Set the working directory in the container
WORKDIR /app

# Copy the SQL script and Python script into the container
COPY pipeline.py pipeline.py

# Install necessary dependencies
RUN pip install --no-cache-dir pandas

# Set the default entrypoint to bash
ENTRYPOINT ["python", "pipeline.py"]