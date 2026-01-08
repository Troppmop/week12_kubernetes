FROM python:3.11-slim

WORKDIR /app

COPY . .

RUN py -m pip install -r requirements.txt

EXPOSE 8000

CMD ["py", "main.py"]