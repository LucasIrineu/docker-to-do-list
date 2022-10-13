FROM node:14
EXPOSE 3001
ADD node_modules.tar.gz .
COPY ./src ./src
COPY package-lock.json .
COPY package.json .
CMD ['npm', 'start']