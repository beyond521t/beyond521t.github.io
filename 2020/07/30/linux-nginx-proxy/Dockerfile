FROM hub.c.163.com/public/nginx:1.2.1
#是表示从官方的node镜像作为基础镜像编译

MAINTAINER tao

# 编译的时候，复制当前目录所有文件到 镜像中 镜像的/dist目录下
#COPY dist/ /usr/share/nginx/html/
#COPY nginx.conf /etc/nginx/nginx.conf

RUN echo 'echo init ok!'


# docker build -t nginx/proxy .
# .表示当前目录，dangjian 构建之后镜像名称

# centOS docker运行容器命令
# docker run -itd --restart=always -p 80:8080 --name nginx -v /data/docker/dangweb/dist/:/usr/share/nginx/html/ -v /data/docker/dangweb/nginx.conf:/etc/nginx/nginx.conf nginx/proxy

# macOS docker运行容器命令
# docker run -itd --restart=always -p 80:80 --name nginx_proxy -v ${HOME}/Documents/docker/nginx/nginx.conf:/etc/nginx/nginx.conf -v ${HOME}/Documents/docker/nginx/ssl/:/etc/nginx/ssl/ nginx/proxy

