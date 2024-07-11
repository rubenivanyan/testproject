FROM node:18 AS development
ENV NODE_ENV=development
WORKDIR /app
COPY package.json yarn.lock /app
RUN yarn install --frozen-lockfile
COPY . .
CMD ["yarn","start"]
