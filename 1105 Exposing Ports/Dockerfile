FROM ubuntu:18.04
RUN apt-get update && apt-get install -y iproute2 iputils-ping traceroute apache2
EXPOSE 80
ENTRYPOINT ["apache2ctl"]
CMD ["-D", "FOREGROUND"]