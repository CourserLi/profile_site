# 使用一个轻量 Web 服务器 Nginx 作为基础
FROM nginx:alpine

# 将本地的 html 文件夹，直接复制到 Nginx 默认的网站目录中
COPY ./ /usr/share/nginx/html

# 暴露容器的 80 端口
EXPOSE 80