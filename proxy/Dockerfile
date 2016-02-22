# https://registry.hub.docker.com/_/nginx/
FROM nginx:1.9.11

# SSL証明書をコピー
#COPY ssl/server.crt /usr/local/nginx/conf/server.crt
#COPY ssl/server.key /usr/local/nginx/conf/server.key

# 設定ファイルをコピー
COPY conf/nginx.conf /etc/nginx/nginx.conf

# HTMLファイルをコピー
COPY html /usr/share/nginx/html
