FROM nginx:1.21
ARG PORT
ENV PORT=${PORT:-3001}
COPY ./dist /usr/share/nginx/html
COPY ./docker/nginx/default.conf.template /etc/nginx/templates/
