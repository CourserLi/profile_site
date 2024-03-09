# 使用一个已有的 Nginx 镜像作为基础
FROM nginx:latest

# 将本地的 html、css 和 js 文件复制到镜像的 /usr/share/nginx/html 目录中
ADD . /usr/share/nginx/html

# 暴露容器的 80 端口
EXPOSE 80
