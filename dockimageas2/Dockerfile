FROM ubuntu:latest
RUN mkdir /app
WORKDIR /app
RUN apt-get update
RUN apt-get install python3 -y
RUN echo "print('Hello Word')" > hello.py
CMD python hello.py