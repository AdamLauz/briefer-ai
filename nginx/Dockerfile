FROM nginx:latest

RUN rm /etc/nginx/conf.d/default.conf
COPY nginx.conf /etc/nginx/conf.d/

COPY ./certs/ngnix_streamlit.crt /etc/nginx/ssl/ngnix_streamlit.crt
COPY ./certs/ngnix_streamlit.key /etc/nginx/ssl/ngnix_streamlit.key