FROM node:8-stretch

WORKDIR /darkwire

COPY package.json .
RUN yarn install --prod

COPY . .
RUN yarn build

EXPOSE 3000
CMD ["yarn", "start"]