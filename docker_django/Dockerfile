FROM python:3.8-slim-buster
ENV PYTHONUNBUFFERED=1
WORKDIR /app
COPy requirements.txt requirements.txt
RUN pip3 install -r requirements.txt
COPY . .
CMD ["python3", "manage.py", "runserver", "127.0.0.1:8000"]