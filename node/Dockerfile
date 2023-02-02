FROM node:current-alpine
COPY . /app
WORKDIR /app
RUN npm install -g npm@7.0.0 && \
    npm i
ENTRYPOINT ["npm", "start"]