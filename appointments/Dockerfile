# Use an official Python runtime as a base image
FROM python:3.10
WORKDIR /app
COPY . /app
RUN pip install flask
EXPOSE 7070
CMD ["python", "app.py"]
