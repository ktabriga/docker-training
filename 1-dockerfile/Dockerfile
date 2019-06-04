FROM ubuntu:16.04

RUN apt-get update && apt-get install -y nginx && apt-get clean
EXPOSE 80
EXPOSE 443
CMD ["nginx" , "-g", "daemon off;"]
