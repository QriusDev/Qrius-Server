FROM nginx:latest
COPY ./nginx.conf /etc/nginx/nginx.conf
# RUN apt update && \
#     apt install python3 python3-venv libaugeas0 -y && \
#     python3 -m venv /opt/certbot/ && \
#     /opt/certbot/bin/pip install --upgrade pip && \
#     /opt/certbot/bin/pip install certbot certbot-nginx && \
#     ln -s /opt/certbot/bin/certbot /usr/bin/certbot
COPY ./certs/fullchain.pem /etc/ssl/certs/fullchain.pem
COPY ./certs/privkey.pem /etc/ssl/private/privkey.pem