FROM nginx:1.12

#  default conf for proxy service
COPY ./default.conf /etc/nginx/conf.d/default.conf

# NOT FOUND response
COPY ./html/ /var/www/html/

# Proxy configurations
COPY ./includes/ /etc/nginx/includes/
