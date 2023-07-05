FROM node:18-alpine3.15

COPY . .

RUN npm install -g json-server

EXPOSE 3005

ENTRYPOINT [ "json-server", "--watch", "db.json", "--port", "3005", "--host", "0.0.0.0" ]