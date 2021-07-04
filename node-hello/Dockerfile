FROM node:10.15.3-alpine
USER root
WORKDIR /node-hello/
COPY    node-hello/ ./
RUN     npm install
EXPOSE 3000
CMD [ "npm", "start"]