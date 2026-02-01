FROM node:18.9.1

WORKDIR /app
COPY package.json /app
RUN npm install 

COPY . /app

expose 5173

CMD ["npm", "run","dev"]


