# Use an official Python runtime as a parent image
FROM docker.io/python:3-slim

ENV FLASK_APP="AppSin"

# Set the working directory to /app
WORKDIR /app

# Copy the current directory contents into the container at /app
COPY . /app

# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

# Make port 5000 available to the world outside this container
EXPOSE 5000

# Run app.py when the container launches
#CMD ["flask", "run", "-p", "5000"]
CMD ["python", "./app.py"]