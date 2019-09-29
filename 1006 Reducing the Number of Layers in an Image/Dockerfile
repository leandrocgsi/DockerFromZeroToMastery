#Simple Udemy Web Server
FROM ubuntu:18.04
RUN apt-get update && apt-get install -y \
        apache2 \
        apache2-utils \
        vim \
        && apt-get clean \
		&& rm -rf /var/lib/apt/lists/* /tmp/* /var/tmp/*		
EXPOSE 80
CMD ["apache2ctl", "-D", "FOREGROUND"]