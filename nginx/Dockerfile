FROM nginx:1.15.0-alpine

# RUN rm /etc/nginx/conf.d/default.conf

# Copie o arquivo de configuração do Nginx
COPY nginx.conf /etc/nginx/nginx.conf
# COPY nginx.conf /etc/nginx/conf.d/default.conf

# ENTRYPOINT [ "/docker-entrypoint.sh"]

CMD ["nginx", "-g", "daemon off;"]
