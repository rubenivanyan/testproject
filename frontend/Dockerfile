FROM node:19
ENV NODE_ENV=development
WORKDIR /app
COPY package.json yarn.lock /app
RUN yarn install --frozen-lockfile
COPY . .
CMD ["yarn","start"]
