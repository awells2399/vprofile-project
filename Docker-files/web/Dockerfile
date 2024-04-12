FROM nginx
LABEL "project"="vprofile"
LABEL "Author"="Aaron Wells"

RUN rm -rf /etc/nginx/conf.d/default.conf
COPY nginvproapp.conf /etc/nginx/conf.d/vpro.conf