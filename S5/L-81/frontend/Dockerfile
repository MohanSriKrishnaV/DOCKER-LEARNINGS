FROM node:14
WORKDIR /app
COPY  package.json /app
RUN npm install
COPY . .
EXPOSE 3000
CMD [ "npm","start" ]