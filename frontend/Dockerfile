FROM node:19-alpine AS development
ENV NODE_ENV=development
WORKDIR /react-app
COPY package.json /react-app
RUN apk add npm
COPY . .
RUN /usr/local/bin/yarn install
CMD ["yarn","start"]
