FROM python:3.8.10-slim
WORKDIR /app
COPY . .
RUN pip install -r requirements.txt
CMD python3 manage.py migrate && python3 manage.py runserver 0.0.0.0:8000
