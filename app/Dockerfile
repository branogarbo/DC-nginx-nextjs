FROM node:12
WORKDIR /docker-nginx
COPY package*.json ./
RUN npm install
COPY src/ ./
RUN npm run build
EXPOSE 3000
CMD [ "npm", "start" ]