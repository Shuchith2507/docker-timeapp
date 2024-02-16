FROM node:alpine3.19
WORKDIR /app
COPY . /app
ENV CREATEDBY=Shuchith
RUN npm install
LABEL maintainer_email="shuchithbu@gmail.com"
LABEL maintainer_rollNumber="421"
CMD ["node", "./src/app.js"]
EXPOSE 2000
