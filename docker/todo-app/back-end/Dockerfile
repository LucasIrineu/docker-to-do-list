FROM node:14
EXPOSE 3001
WORKDIR /app
COPY ['node_modules.tar.gz', '.']
COPY ['./src', './src']
COPY ['package-lock.json', './']
COPY ['package.json', './']
RUN npm install
ENTRYPOINT ['npm', 'start']