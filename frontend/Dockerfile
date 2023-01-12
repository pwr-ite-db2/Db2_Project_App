FROM node:19-alpine3.16

ADD build ./build
EXPOSE 3000

RUN npm i serve -g
ENTRYPOINT ["serve", "-s", "build"]
