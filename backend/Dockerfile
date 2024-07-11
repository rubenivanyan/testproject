FROM node:18 AS development
ENV NODE_ENV=development
WORKDIR /app
COPY package.json yarn.lock tsconfig.build.json ./
RUN yarn install --frozen-lockfile
COPY . .
CMD ["yarn","start"]
