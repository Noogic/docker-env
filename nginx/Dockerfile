FROM nginx:latest

ADD nginx.conf /etc/nginx/
ADD app.conf /etc/nginx/conf.d/

ADD upstream.conf /etc/nginx/conf.d/upstream.conf

RUN usermod -u 1000 www-data

CMD ["nginx"]

EXPOSE 80 443
