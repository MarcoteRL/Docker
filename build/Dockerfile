FROM alpine

RUN echo "hola desde el contenedor";
RUN mkdir /app
COPY src /app
RUN chmod 777 /app/tren.sh
RUN apk add sl --no-cache
CMD app/tren.sh