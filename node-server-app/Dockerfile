FROM alpine:latest

LABEL maintainer_email="shuchithbu@gmail.com"
LABEL maintainer_rollNumber="421"
RUN apk add --update npm

WORKDIR /app
COPY . /app

RUN npm install

CMD ["node", "./src/app.js"]
