FROM node:14
EXPOSE 3001
WORKDIR /todo-app
ADD node_modules.tar.gz .
COPY Dockerfile /usr/local/bin/
ENTRYPOINT [ "npm", "start" ]