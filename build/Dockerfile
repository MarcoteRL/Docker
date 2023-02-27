FROM ubuntu:18.04

RUN apt-get update \
        && apt-get install -y --no-install-recommends sl
RUN mkdir /app
COPY src /app
RUN chmod 777 /app/tren.sh
CMD app/tren.sh