FROM debian:bookworm-backports

RUN apt update && apt install -y nginx 

COPY nginx.conf /etc/nginx/nginx.conf

EXPOSE 80

CMD ["nginx", "-g", "daemon off;"]

