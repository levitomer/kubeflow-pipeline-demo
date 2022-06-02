FROM python:3.7-slim

WORKDIR /app

RUN pip install -U sklearn numpy

COPY preprocess.py ./preprocess.py

ENTRYPOINT [ "python", "preprocess.py" ]