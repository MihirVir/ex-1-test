FROM node:alpine

WORKDIR /app
COPY ./package.json ./package.json
COPY . .
RUN npm install
EXPOSE 8081

CMD ["npm", "run", "start"]
