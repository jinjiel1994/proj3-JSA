FROM python:3.5
MAINTAINER Jim Li "jinjiel@uoregon.edu"
RUN apt-get update -y
RUN apt-get install -y python-pip python-dev build-essential
COPY . /flask_vocab
WORKDIR /flask_vocab
RUN pip install -r requirements.txt
ENTRYPOINT ["python"]
CMD ["flask_vocab.py"]
