FROM nginx
COPY code /usr/share/nginx/html
COPY expense.conf /etc/nginx/conf.d/expense.conf
RUN rm -f /etc/nginx/conf.d/default.conf  