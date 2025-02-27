FROM nginx 
RUN rm -rf /etc/nginx/nginx.conf
RUN rm -rf /etc/nginx/conf.d
COPY code /usr/share/nginx/html/
COPY nginx.conf /etc/nginx/nginx.conf 
#COPY expense.conf /etc/nginx/conf.d/expense.conf 



