FROM node:14

WORKDIR /app/frontend

COPY package*.json /app/frontend

RUN npm install

COPY . /app/frontend/

EXPOSE 8080

CMD ["npm", "run", "serve"]