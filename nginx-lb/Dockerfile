FROM nginx
USER root
MAINTAINER tprinz@redhat.com
RUN rm /etc/nginx/conf.d/default.conf
COPY ./etc/nginx/conf.d/default.conf /etc/nginx/conf.d/default.conf
