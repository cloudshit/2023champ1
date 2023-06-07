FROM python:3.8-alpine

RUN apk add --no-cache curl

RUN pip install flask

COPY green.py .

CMD ["python", "green.py"]
