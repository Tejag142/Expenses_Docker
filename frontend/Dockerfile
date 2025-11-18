FROM nginx
RUN rm -rf /usr/share/nginx/html/*
COPY expense.conf /etc/nginx/default.d/expense.conf
COPY static/ /usr/share/nginx/html/static
COPY index.html /usr/share/nginx/html/
COPY robots.txt /usr/share/nginx/html/
COPY asset-manifest.json /usr/share/nginx/html/
