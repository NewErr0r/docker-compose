FROM nginx
RUN rm /etc/nginx/conf.d/default.conf
COPY index.html /usr/share/nginx/html
COPY nginx.conf /etc/nginx
EXPOSE 2222
CMD ["nginx", "-g", "daemon off;"]
