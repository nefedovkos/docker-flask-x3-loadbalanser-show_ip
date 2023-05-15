FROM python:3.10-alpine

WORKDIR /app

RUN pip install redis
RUN pip install Flask

COPY app.py .

CMD ["python", "app.py"]
