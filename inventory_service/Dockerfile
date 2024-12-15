FROM python:3.12-slim

WORKDIR /inventory

COPY requirements.txt requirements.txt

RUN pip install -r requirements.txt

COPY inventory_service/ .

EXPOSE 8082

CMD ["python", "inventory_app.py"]