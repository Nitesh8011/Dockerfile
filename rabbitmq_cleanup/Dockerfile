FROM python:3.9.20

MAINTAINER nitesh.kumar

RUN apt-get update

COPY requirement.txt .
COPY main.py .

RUN pip install -r requirement.txt
ENTRYPOINT [ "python3", "main.py" ]