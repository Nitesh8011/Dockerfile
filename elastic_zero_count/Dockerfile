FROM python:3.9.20

MAINTAINER nitesh.kumar

RUN apt-get update

COPY main.py requirement.txt .
RUN pip install -r requirement.txt

ENTRYPOINT [ "python3", "main.py" ]