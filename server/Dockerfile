FROM node:18-alpine
WORKDIR /app
COPY . /app
COPY package.json /app/package.json
RUN npm install
EXPOSE 5000 
USER node
CMD ["node", "index.js"]