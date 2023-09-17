FROM python:3.10-slim-buster
#
#RUN apt-get update \
#  && apt-get install -y curl \
#  && curl --version \
#  && apt-get clean autoclean \
#  && apt-get autoremove -y \
#  && rm -rf /var/lib/apt/lists/*

#
WORKDIR /app
COPY . /app



## rest port
#EXPOSE 7790

#
CMD python ./main.py
