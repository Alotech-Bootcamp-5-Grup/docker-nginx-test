FROM node:lts
WORKDIR /umm-server
COPY package*.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]
