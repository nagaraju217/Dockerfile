FROM almalinux:9
RUN mkdir /app
WORKDIR /app
RUN dnf install nginx -y
RUN useradd raju
USER raju
RUN pwd

CMD [ "sleep", "1000" ]