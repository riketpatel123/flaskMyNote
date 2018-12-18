FROM python:2.7

ADD . /app
WORKDIR /app
RUN pip install -r requirements.txt

EXPOSE 5000
CMD python flaskr/flaskr.py
