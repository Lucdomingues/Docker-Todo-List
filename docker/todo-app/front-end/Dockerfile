FROM node:14
EXPOSE 3000
WORKDIR /todo-app
ADD node_modules.tar.gz .
COPY Dockerfile /usr/local/bin/
ENTRYPOINT [ "npm", "start" ]