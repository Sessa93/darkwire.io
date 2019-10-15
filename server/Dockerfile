FROM node:8-stretch

WORKDIR /darkwire

COPY package.json .
RUN yarn

COPY . .
RUN ./build.sh

EXPOSE 3030
CMD ["yarn", "start"]