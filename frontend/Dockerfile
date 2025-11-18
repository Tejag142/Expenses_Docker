FROM nginx
RUN rm -rf /usr/share/nginx/html/*
ADD expense.conf /etc/nginx/default.d/expense.conf
ADD static/* /usr/share/nginx/html/
ADD index.html /usr/share/nginx/html/
ADD robots.txt /usr/share/nginx/html/
ADD asset-manifest.json /usr/share/nginx/html/
