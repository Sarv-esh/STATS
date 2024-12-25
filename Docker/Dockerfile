FROM nginx:latest
LABEL author="sarvesh"
COPY index.html /usr/share/nginx/html
EXPOSE 80
CMD [ "nginx","-g","daemon off;" ]


FROM ubuntu:latest

RUN apt-get update && apt-get install -y apache2

