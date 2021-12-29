FROM node:lts
WORKDIR /umm-client
COPY package*.json ./
RUN npm install
COPY . .
CMD ["npm", "start"]
