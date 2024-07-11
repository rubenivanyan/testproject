FROM node:18 AS development
ENV NODE_ENV=development
WORKDIR /app
COPY frontend/package.json /app
RUN npm install -g npm@10.8.2
COPY . .
RUN /usr/local/bin/yarn install
CMD ["yarn","start"]
