FROM ubuntu_with_python
MAINTAINER Lee Li
RUN apt-get update && \
    apt-get install -y python

COPY  hello.py .
ENTRYPOINT [ "python","hello.py"]