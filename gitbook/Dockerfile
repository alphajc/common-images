FROM node:12.14

LABEL maintainer="Jerry Chan<jerry@mydrem.ink>"

WORKDIR /tmp

RUN npm set registry https://registry.npm.taobao.org \
    && npm -g install gitbook-cli \
    && gitbook init