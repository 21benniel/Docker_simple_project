FROM python:3.7-slim

WORKDIR /app

ADD . /app
RUN pip install --upgrade pip
# Install any needed packages specified in requirements.txt
RUN pip install -r requirements.txt

# Make port 80 available to the world outside this container
EXPOSE 80


CMD ["python","app.py"]
