FROM debian:bookworm-slim

RUN apt update && apt install -y apache2

COPY ./index.html /var/www/html

EXPOSE 8080

CMD ["apache2ctl", "-D", "FOREGROUND"]