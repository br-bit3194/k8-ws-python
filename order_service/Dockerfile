FROM python:3.12-slim

WORKDIR /order

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

COPY order_service/ .

EXPOSE 8083

CMD ["python", "order_app.py"]

