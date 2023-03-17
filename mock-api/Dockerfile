FROM python:slim

RUN pip install fastapi \
pip install uvicorn

WORKDIR /app

COPY mock-api/main.py /app

CMD ["uvicorn", "main:app", "--host", "0.0.0.0", "--port", "8080"]