FROM python:3.8.5
WORKDIR /app
COPY requirements.txt .
RUN pip3 install -r requirements.txt --no-cache-dir
COPY . /app
ENV PYTHONPATH "${PYTHONPATH}:/app/api_yamdb"
CMD ["gunicorn", "api_yamdb.wsgi:application", "--bind", "0:8000" ]
