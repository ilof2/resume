FROM python:3.7.2-stretch

WORKDIR resume/
ADD . /resume/

RUN pip install -r requirements.txt

CMD gunicorn --bind 0.0.0.0:5000 main:app