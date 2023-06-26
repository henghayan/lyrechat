# 基于官方Nginx镜像
FROM nginx

# 将你的nginx配置文件复制到容器中
COPY nginx.conf /etc/nginx/nginx.conf

# 暴露端口
EXPOSE 80
EXPOSE 443

# 运行nginx
CMD ["nginx", "-g", "daemon off;"]
