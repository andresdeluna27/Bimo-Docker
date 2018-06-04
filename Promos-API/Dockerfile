FROM python:3.5-slim

WORKDIR /app

ADD . /app

RUN pip install --trusted-host pypi.python.org -r requirements.txt

EXPOSE 5001

CMD ["python3","setup.py","run"]
