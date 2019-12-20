FROM registry.cn-hangzhou.aliyuncs.com/aliyun-node/alinode:3

ENV PM2_VERSION 3.5.2
RUN npm install -g pm2@${PM2_VERSION} \
  && mkdir -p /opt/app

WORKDIR /opt/app

EXPOSE 3000
