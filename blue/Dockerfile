FROM python:3.8-alpine

RUN apk add --no-cache curl

RUN pip install flask

COPY blue.py .

CMD ["python", "blue.py"]
