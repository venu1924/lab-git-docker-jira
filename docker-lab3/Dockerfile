# Dockerfile1
FROM node:20-alpine
WORKDIR /usr/src/app
COPY package.json .
COPY app.js .
RUN npm install --production
EXPOSE 3000
CMD ["node", "app.js"]
