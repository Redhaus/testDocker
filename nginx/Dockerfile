#user nGinx image
FROM nginx

#remove default config file
RUN rm /etc/nginx/conf.d/default.conf

#replace with our own
COPY nginx.conf /etc/nginx/conf.d/