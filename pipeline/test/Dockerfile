FROM python:3.7-slim

WORKDIR /app

RUN pip install -U sklearn numpy

COPY test.py ./test.py

ENTRYPOINT [ "python", "test.py" ]