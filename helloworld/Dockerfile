from python:3.11.1-buster

WORKDIR /

RUN pip install runpod

ADD handler.py .
ADD http://date.jsontest.com /etc/build-date

CMD [ "python", "-u", "/handler.py" ]
