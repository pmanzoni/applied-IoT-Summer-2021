FROM alpine:latest

RUN apk add --update python3 py3-pip

RUN pip install paho-mqtt

COPY sisubttn2.py /home/

CMD ["python3", "/home/sisubttn2.py"]

