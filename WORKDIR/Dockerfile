FROM almalinux:9
RUN mkdir /app
WORKDIR /app
RUN dnf install nginx -y
RUN useradd raju
USER raju

CMD [ "sleep", "1000" ]