# 使用轻量级 Nginx 镜像作为基础
FROM nginx:alpine

# 设置工作目录
WORKDIR /usr/share/nginx/html

# 复制所有网站文件到容器中
COPY . .

# 暴露 80 端口（Nginx 默认端口）
EXPOSE 80

# 启动 Nginx 服务器（基础镜像已有默认命令）
# CMD ["nginx", "-g", "daemon off;"]