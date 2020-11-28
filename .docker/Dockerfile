FROM nginx:1.17.4-alpine AS nginx
LABEL MAINTAINER = 'Henny Krijnen <krijnen.h@gmail.com>'

COPY .docker/nginx/conf.d /etc/nginx/conf.d
COPY ./app /srv/
